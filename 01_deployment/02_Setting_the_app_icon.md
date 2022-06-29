1. Open [**https://pub.dev**](https://pub.dev)

2. Type **flutter_launcher_icons**:

**![screenshot](https://lh4.googleusercontent.com/0CJV39bWGrAkhlCUkkLRK4H6iM851fIrwUQtpYYlUQH8ZDC1kU6IfJivaB9xg49ABhGCABPF3AVe2918U0PFYtPoL9awW2hTNsxEsdpDskLtCWISnkkh879m80ja53NlEpdp8vYZ)**

3. Click the **Copy** button to copy the packages:

![screenshot](https://lh5.googleusercontent.com/tRPdaH7HmUG9T8mBdDV1oXVi5XGuOZd5843-MltdLeaAPyUAVw0bMrn5EGLiBvVrkP-VLEyz65nGojQmmMam9RH7UXNZlJHXli9kC8MxldYtHdQW1MM8o5xNXY-ZAtUEmRaY_QfW)

4. Open the **pubspec.yaml** file:

![screenshot](https://lh6.googleusercontent.com/kiVeYZHMaSW1yaGwJGKvReEwI25cnu0NL19zpH0IqHjxDOJV-pkMjENzC_cm7E-9nhxvr8SHS6fSdNv_tc_96UuQvJL71JcrymDJV1ZLmVY95ecilrcJEpT_4T2Hwv19bNvHcbhu)

5. Under the `dev_dependencies`, paste the **flutter_launcher_icons** package:

![screenshot](https://lh4.googleusercontent.com/gp6U35IU1R0Xvna7JX-swGylh5ezNoeqc5t6qlBDcjF1dZ8abNn8qmlQkcsEPAWfv2cuPpOgFPnS8jhTkAYKQT0m6qaEwjFLcdI7b32jnOj0OKWmaYJIQvXG9XnWObZQ2XR1zfJz)

6. Click the **Get packages** button as shown below:

![screenshot](https://lh4.googleusercontent.com/IIiMokXJN2A9PY8hxXEZUEmMYdw4jywXy-yPSAJz20oTJlsLw99p1wDy5V92MgGk2QQLbbb_z4PPELMBeahlC8HoDfWp-9I0hyT7TX1MMhMUWvsNR8Fq9u-f-PuQJloKZeE3Z3WU)

7. Paste the codes below under **flutter_launcher_icons**, and be careful about the spaces:

```yaml
flutter_icons:
  ios: true
  android: true
  remove_alpha_ios: true
  image_path: "assets/icon.png"
```

![screenshot](https://lh3.googleusercontent.com/EAVjfRI4jxmLUbuljMpXM7ySTfVy6RXErg-ieumuDs3rcHToXAh6Knb-tOw6DcWVgeqBqY5c3mpuRpyJ6uksmEy9O6nqPF7n3jxQoVWgc6qRi7XFSaQYxvgQDSRU8OTy971JNOjH)

8. Create an **assets** folder inside the root of the `notes_app_riverpod` project.

![screenshot](https://lh6.googleusercontent.com/Xrz0EdLpPRNaMmHsuywV03aFMkzEOczuYjSig33uK2olGUSCBvG6Ye_tOqicXU3Y3MqJaGj6S__SgNDDSzI-OXnzP8Nqbl-kBecb53PkWUuCChMsZeTlscgebEFq98Ah4QJZ1jm_)

9. Add the **icon.png** image inside the **assets** folder.

> You can add your icon image, and rename it to “**icon.png**”. Or download [this icon](https://github.com/Northwest-content/flutter_assets/blob/main/Module_9/note.png)

10. Open **Terminal**:

![screenshot](https://lh6.googleusercontent.com/10Nb2DMFMyhMUROEsbazMZPvGRgPY_GgeLYjdwUKvb6Dg66D2vYqbPy09I4GzOppPgC4OPzx_z9zUDTwThHf-FZmGRLrS5_xQptA91PvEhFXr-ODT9tE-H_RRxixAdqkbyUa9M23)

11. Make sure that the path in terminal is your flutter project folder. If you are not inside the correct path, run the **cd** command to navigate to the flutter project.

12. Run the following command:

```shell
flutter pub run flutter_launcher_icons:main
```

![screenshot](https://lh6.googleusercontent.com/TgWKv6xxwPugCNHusEJJnVAebKW4iGunKc0D9liK598M8RIztshPXyE1xj_FOBYzoP5niGNYq6mdrgJlclO633b8Z5C9R2gW5VmQ6zfH3xkURgwYvsK2Tg2WOyc42iM0KBT3bEwZ)
