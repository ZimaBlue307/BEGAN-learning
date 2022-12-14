# BEGAN-learning
Parameter Tuning of BEGAN and Comparison of Different GANs

This technical report summarizes the development process, theory and application fields of adversarial neural networks, and firstly completes the reproduction and training of BEGAN. Compared with GAN, BEGAN uses a new way of evaluating the quality of generator generation, so that BEGAN no longer has to worry about mode collapse and training imbalance problems, even with simpler networks, or without training tricks or using SELU The activation function can also achieve better training results. 

After successfully reproducing and training BEGAN, experiments are designed to tune the parameters of the initial generation rate of the discriminator and generator in BEGAN. Based on the comparison of the convergence results visualized by Tensorboard and the quality of the generated images, it is found that the initial learning rate of the model is set to about 0.0001, so that the training of the model can obtain ideal results. 

Finally, the analysis and comparison between the BEGAN model and the original GAN model are completed with FID, Precision, Recall, etc. as evaluation indicators. It is concluded that there is no absolute advantage between the models, and more careful research should be conducted on the robustness of the results when improving the model, rather than just observing the sampling error. It also provides critical thinking on related papers published by the Google team.
