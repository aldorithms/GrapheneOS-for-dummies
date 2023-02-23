# GrapheneOS-for-dummies
An unofficial dumb down guide to using the Graphene Operating System, that is also useful for hardening your pre-existing Android OS.

## First Apps
GrapheneOS intentionally doesn't bundle apps that weren't either made by them or by the AOSP project. This is intentionally designed to reduce the number of trusted parties. GrapheneOS is already a fork of AOSP, so logically the only other trusted party that should be allowed to bundle apps is GrapheneOS. The apps included with GrapheneOS don't use very many permissions anyway, for security reasons. If for some reason, there is a vulnerability within these apps, a hakcer/malware could piggy back off the app and gain the same privileges the it has. This is called privilege escalation. The fewer permissions the app has, the smaller your system's attack surface.

### Apps
A hardened application suite that at this moment is only designed to deliver GrapheneOS apps. This appstore has an apk available for all Android devices, but for GrapheneOS users, it is not necessary to download it.

#### PDF Viewer
https://github.com/GrapheneOS/PdfViewer
A javascript hardened PDF Viewer designed to 

### Accrescent
A privacy/security focused app store written in Jetpack Compose. This application is currently in alpha, and thus has a limited amount of applications  and features written to it. Despite this, it is still a good choice to start you off, as it is a first of a kind appstore that offers

### Obtainium
