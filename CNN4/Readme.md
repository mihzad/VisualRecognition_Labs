got mode collapse by:
1) decoupling learning rates for distriminator & generator, reducing one for discriminator
2) making generator "overrun" discriminator by training it 8 times per 1 discriminator train.
<img width="242" height="242" alt="image" src="https://github.com/user-attachments/assets/695537dc-790b-4adf-8c75-f33276ef5aeb" />

see results_mode_collapse folder & console output for details.
