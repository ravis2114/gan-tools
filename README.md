# gan-tools
A handy tool to understand GAN architecture and use it on the go. also encompasses ways to train on GPUs as well as TPUs.

### GPU
----
Output after training DCGAN for 50 epochs
----
![dcgan on gpu](https://github.com/ravis2114/gan-tools/blob/main/output/dcgan.gif)

### TPU
----
Output after training DCGAN for 50 epochs
----
![dcgan on tpu](https://github.com/ravis2114/gan-tools/blob/main/output/dcgan_tpu.gif)

At lower fps:
----
![dcgan on tpu at lower fps](https://github.com/ravis2114/gan-tools/blob/main/output/dcgan_tpu_fps.gif)

### Models
----
trained on GPU
----
[generator][link5]

[discriminator][link4]

trained on TPUs
----
[generator][link7]

[discriminator][link6]

License
--
[MIT][link1]


[link1]: <https://github.com/ravis2114/gan-tools/blob/main/LICENSE>
[link4]: <https://github.com/ravis2114/gan-tools/blob/main/models/GPU/discriminator.h5>
[link5]: <https://github.com/ravis2114/gan-tools/blob/main/models/GPU/generator.h5>
[link6]: <https://github.com/ravis2114/gan-tools/blob/main/models/TPU/discriminator_tpu.h5>
[link7]: <https://github.com/ravis2114/gan-tools/blob/main/models/TPU/generator_tpu.h5>
