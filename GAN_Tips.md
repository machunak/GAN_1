Tips

1. (-1, 1) norm
    .uniform(-1, 1)
    .transforms

2. Generator 마지막 tanh

3. min(log(1-D)) -> max(log(D))

4. train Generator label : fake =: real
                           real =: fake

5. BN -> mini batch

6. Discriminator : LeakyReLU

7. DCGAN -> KL + GAN / VAE + GAN

8. Adam - D : SGD
          G : Adam

9. 학습시 loss 관찰 -> G D loss 불균형 don't care

10. G(z)
    add g n 모든 layer G : GV