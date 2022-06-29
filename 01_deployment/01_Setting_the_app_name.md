1. Fork and clone the notes app project from [GitHub](https://github.com/Northwest-content/flutter_notes_app), open it in VS Code, and get the packages.

2. Change the app's name:

### For **Android**:

**a.** Open the **AndroidManifest.xml** file:

    > Android > src > main > Androidmanifest.xml

![screenshot](https://lh6.googleusercontent.com/r0RfUXuSq0XVnd3-1GH0mnCzB5JE_GyF85nBNSpFKco1oUdvGK_twYNIsVnYJ2ncBhSuA2Jt-91I7Wssd1sA7uc_KuSUZiDulyMNZCR0ZU8Pv_z7xmCkEZXPGzo433D_5oATiZd8)

**b.** Change `android:label = "YOUR_APP_NAME"` to `android:label = "Notes"`

![screenshot](https://lh3.googleusercontent.com/P8hqQ4BOBcCVi4bpPmf6y-nxiQczizQpPJu0KiLTBKIdKPJaFixXKNfuKRk_-Jm5RIoCLQi2i96rkHD-_F7H-f0BzPOjgvJuc4mV3HyCF8C39EfSn5MyW4IhFGWofOCesaLuNmiM)

### For **iOS**:

**a.** Open the **Info.plist** file:

    > ios > Runner > Info.plist

**![screenshot](https://lh5.googleusercontent.com/mezLt34-6O9yN2Xk6K8hKDXjgdIQC4o7d-Xmy-4ChyvXduXp5S8VM4MwsEtSgIQeKgVbB8RJSxlsoGy2963ScpL9A1oZhPa0_wMV5SfVibMVIGcBFVMg2f3j94VW5BxAjT_fpQsC)**

**b.** Change **CFBundleName**:

```
<key>CFBundleName</key>
<string>You App Name</string>
```

to

```
<key>CFBundleName</key>
<string>Notes</string>
```

![screenshot](https://lh5.googleusercontent.com/zGFsxiKuhUcTpDtkWLJsRbB5lv6Dzb3Y0NGuj38UnaeeZyOBZQY24pAa3cUYM8Gs-H1RkVBT6ssmO1kxeij9RfoXGuYURcLPZqhCUmjKUVJiXQHJFPzmlg1AWOz1WCIcp4sCzWdR)
