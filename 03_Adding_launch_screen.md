# Adding a launch screen



1. Open [**https://pub.dev**](https://pub.dev)
2. Type **flutter_native_splash**

**<img src="https://lh6.googleusercontent.com/EFLZqoaQcHm6dm_JNLxN2Y94-kqK2eguJmVZb0_IZk18VvoeyPPwyz6EljhK-FS9nS4hWgrF-3QCqfOuwdkojia-z6OkXEBq6vbQBxtJXRC7FKk4mxIgnTQeS8rLvLZ1_5PI3-fF" alt="img" style="zoom:50%;" />**





3. Click the **Copy** button

   <img src="https://lh5.googleusercontent.com/AUIK4d4-ZKj86vyC1hUUKaI8AG9XA7oI5EKLZd6Kt7A4mgn4-saXfqlAYUwjtL-vPHlVKjbfHgQcfHleXUdud8ThYAa5z-OGH6NtJF8-T4OE5EVAUN4TwlMKNsmvW0s4VAnviKgn" alt="img" style="zoom: 50%;" />

4. Open the **pubspec.yaml** file

   <img src="https://lh6.googleusercontent.com/kiVeYZHMaSW1yaGwJGKvReEwI25cnu0NL19zpH0IqHjxDOJV-pkMjENzC_cm7E-9nhxvr8SHS6fSdNv_tc_96UuQvJL71JcrymDJV1ZLmVY95ecilrcJEpT_4T2Hwv19bNvHcbhu" alt="img" style="zoom:67%;" />







5. Under the `dev_dependencies` paste **flutter_native_splash** package

![img](https://lh6.googleusercontent.com/ehm0a0QFuPVjNvWKHOsxqSOK3ok9lFVJWeV6ryiP-Bpj4p7VR3g8zI_1zRGswnJ7CS0S0KxE7_IoljxwIDPqJiwaDqH8H0BLDHCF7fcGK5uX08eDo_btcuQ-pqn-3PSDaBzDA3fE)





6. Click **Get** packages

   ![img](https://lh4.googleusercontent.com/IIiMokXJN2A9PY8hxXEZUEmMYdw4jywXy-yPSAJz20oTJlsLw99p1wDy5V92MgGk2QQLbbb_z4PPELMBeahlC8HoDfWp-9I0hyT7TX1MMhMUWvsNR8Fq9u-f-PuQJloKZeE3Z3WU)







7. Paste these codes under the **flutter_launcher_icons**, also make sure about the spaces

```yaml
flutter_native_splash:
  image: assets/splash.png
  color: "#FBFBDC"

```

![img](https://lh3.googleusercontent.com/mvIaEDvAfwK4R9pb1fqhPP6elYYFrZhKnIt_AKltZP8kuFWmqiXhQmyIcdtFDQJnNa8qhmOeT4POdVXd9FcXeIpuliVac90JpHg6gexS554FjHvNIn_K4mUYsWjOEyxMuNB1cYmV)

> you can change the background color by changing the **color** value, and this value take HEX color.

> Use this website to get the HEX color, https://htmlcolorcodes.com/



8. Add the **splash.png** image inside the **assets** folder.

   > You can add your splash image, and make sure to name the image “splash.png”. Or download this image: https://github.com/Northwest-content/flutter_assets/blob/main/Module_9/splash.png

![img](https://lh4.googleusercontent.com/PIdgDSXT4MHFo1wOHW0bkdYI_IK4Yq0GSPizwYI7WzYlIc2Kssjn2d8fwE3uIb7WwURrPCCAXkY_fGLfXvnlw_Smu22ET4Z7cK1p0U4-IxoeydSUGRl-LraalwbHhxpMZvx8w0pX)





9. Open the **Terminal** 

![img](https://lh6.googleusercontent.com/10Nb2DMFMyhMUROEsbazMZPvGRgPY_GgeLYjdwUKvb6Dg66D2vYqbPy09I4GzOppPgC4OPzx_z9zUDTwThHf-FZmGRLrS5_xQptA91PvEhFXr-ODT9tE-H_RRxixAdqkbyUa9M23)



10. Make sure the terminal path is your flutter project folder. If you are not inside your flutter project folder; Run the cd command with the flutter project folder. Then click enter.

![img](https://lh4.googleusercontent.com/1q5Uct8RchJrkCrLpLbTthkXmozUaD3FAKd5SeRy0K7tncjkX09hOO_ssYXb557r6xX7--H4xcEb1fDToO0jrtjoRQDa677-cBNk5o2Nvyj3Alp2yYB4ULkZigkvXA9vkLi58hOq)





11. Run,

    ```shell
    flutter pub run flutter_native_splash:create
    ```

    ![img](https://lh3.googleusercontent.com/wRV1ZEDAZWf6tuH4zov3Nk--_X7qBDm-cOTE5Qut15W2y420zLa5HKfGObHCxWQhnL8MSWPCKzxMa9eyH-KQbHw_3ZeZ5Ry7un6l5g5pbuP8IiSv-O0Yy1dOsP_qKRz2F5ii_i3B)







12. Then click **Enter**

**![img](https://lh5.googleusercontent.com/hc6dIsasYWhtCCaXcM6Hqs_Z0WNiIcSoyesOx_ZyIbs0yIfaxiyB9igvTMAwwhwaYLbSIugMRf36_K-nVX59UGxNd2YmmkId9HLTIFJb0XCafCGzwnoVvDWPgB0Fh4v5QSd7SNUD)**









