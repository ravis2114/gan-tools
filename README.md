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
at lower fps:
----
![dcgan on tpu at lower fps](https://github.com/ravis2114/gan-tools/blob/main/output/dcgan_tpu_fps.gif)

### Models
----
trained on GPU
----
[GENERATOR][link5]
[DISCRIMINATOR][link4]
trained on TPUs
----
[GENERATOR][link7]
[DISCRIMINATOR][link6]

License
--
MIT


[link1]: <https://github.com/ravis2114/gan-tools/blob/main/output/dcgan.gif>
[link2]: <https://github.com/ravis2114/gan-tools/blob/main/output/dcgan_tpu.gif>
[link3]: <https://github.com/ravis2114/gan-tools/blob/main/output/dcgan_tpu_fps.gif>
[link4]: <https://github.com/ravis2114/gan-tools/blob/main/models/GPU/discriminator.h5>
[link5]: <https://github.com/ravis2114/gan-tools/blob/main/models/GPU/generator.h5>
[link6]: <https://github.com/ravis2114/gan-tools/blob/main/models/TPU/discriminator_tpu.h5>
[link7]: <https://github.com/ravis2114/gan-tools/blob/main/models/TPU/generator_tpu.h5>
