2IP 2STON Core Project(P2P Security Solution)

<network configuration>
2ston_cam_rpi3_pkg <= P2P security communication => 2stoncam_apk


History for 2ston_cam_rpi3_pkg version 20180131_134518
-------------------------------------------------------
1. Apply the 2ston hole punching method.
   -> hole punching between symmetric nat and every cone nat is possible ;)
2. Fix some log messages and minor bugs.
3. Add install/uninstall scripts.

History for 2stoncam_apk version 0.918(2018.04.05)
--------------------------------------------------
1. Add Napi
- Remove many goto func.
- Seperate channel_open & hole punch logic.
- Change client & channel structure.
2. Change JNI code.

History for 2stoncam_apk version 0.918(2018.03.16)
--------------------------------------------------
1. Add hole punch check.
2. Add son cancel function.

History for 2stoncam_apk version 0.917(2018.03.09)
--------------------------------------------------
1. Fix some small activity bugs.
2. Remove some trash source.

History for 2stoncam_apk version 0.916(2018.02.02)
--------------------------------------------------
1. Fix some core issue.

History for 2stoncam_apk version 0.911(2018.01.30)
---------------------------------------------------
1. Improve the 2ston hole punching method.
2. Fix some log messages.


History for 2stoncam_apk version 0.910(2018.01.29)
---------------------------------------------------
1. Apply the 2ston hole punching method.
   -> hole punching between symmetric nat and every cone nat is possible ;)
2. Fix a bug that is related to socket close(STDIN) 
3. Fix some minor bugs.


History for 2stoncam_apk version 0.906(2017.12.07)
---------------------------------------------------
1. Fix a problem that doesn't automatically reconnect to session server while reloading it.
2. Fix some hole punching bugs.
3. Move session server's location from Google to AWS.
4. Add a password checking code into 2stoncam UI.

Notice: Please uninstall the preinstalled apk at first before installing this version.
If you don't follow this step, this apk will not be run normally because of an internal db file(messed db file).

Best Regards,
2IP 2STON Core Team.
