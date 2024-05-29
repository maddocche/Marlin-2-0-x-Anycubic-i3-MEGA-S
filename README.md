# My custom personalization based on Knutwurst awesome work
Mine is a MEGA S with stock 0.0.3 board and DGUS display, FYSETC TMC2208 V1.2 stepper drivers ([link](https://www.amazon.it/BCZAMD-FYSETC-TMC2208-V1-2-passo-passo/dp/B0CGMWVMPF/ref=sr_1_1?__mk_it_IT=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1QQRPHY7VPGWM&dib=eyJ2IjoiMSJ9.lB055hKyqJxFmAsw1_YneXvtlRQoIa9xjGsh03QpPTlitaR7fK6uDW7pQNjX_AIZ3FLXYGYumsxWnuZMDx6aIsCB-ORJe3WQ9qK8yH49r5cWIIgrAkyMHbqbBvFrmWhxYX5K4pE2hwylpkdFkcxX4EHSYbBNYqTC8pYdzhJkvkZtQZLq2BA-i3cccXN7qFRAsjr9LNaWK4Ho1y8WpZZnjT95kQixwRaL2Yn_SJ5PsoDhXxT9S-qvuxhehEoa9ai6RR9_CQ8I5G2QrgrGKFVl4Ta72GdAwX5y6IEGx2s8gIs.M04G8bqEFT7VxgSYK-as68gZj59Vll6Hj-KwG7yTPOs&dib_tag=se&keywords=fysetc+tmc2208&qid=1717018093&sprefix=fysetc+tmc2208%2Caps%2C66&sr=8-1)), GIANTARM 3D Touch ([link](https://www.amazon.it/Geeetech-3D-Touch-Sensore-stampante/dp/B08HMRWNWX/ref=sr_1_1_sspa?__mk_it_IT=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1CWQJYN5YKSWE&dib=eyJ2IjoiMSJ9.yJ9f0VDeMlWrjY2HyWJbnrs8UtKc28PXTA8CDTPKtFsRsl9QxDiPjs8dSQpIwD-a8fmmPMwvvJymjlpyYhgEWXfklHJlEQImpjh_9Nn_Kc4.8EmI9ueR4Igt2n-h-mw6EjZ9DsUn5NeAhfjPd7Cn5EQ&dib_tag=se&keywords=giantarm%2B3d%2Btouch&qid=1717018382&sprefix=giantarm%2B3d%2Btouch%2Caps%2C79&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1)), MK4 X-Carriage ([link](https://www.thingiverse.com/thing:3537449)), stock E3D V5 Hotend.

It uses the z-probe for homing and bilinear ABL with a 4x4 grid.

Other stuff:
 - switched from PID tuning to MPC tuning ([link](https://marlinfw.org/docs/features/model_predictive_control.html))
 - enabled G34 command for automatic z-gantry alignment
 - removed startup chime
 - incresed default xy jerk to 12.5

Which build to launch? **MEGA_S_DGUS_TMC_BLT_10**