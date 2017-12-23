# Launcher3-Oreo
Android Oreo launcher3 source code

## How to run
We have to modify something for runing the source code.

1. find the ProviderConfig class in src_config, modify AUTHORITY to your authority for avoiding conflict with android launcher
default authority and the thirdparty's.  
2. modify the applicationId in build gradle.  
3. modify AndroidManifest.xml the permission names com.android.launcher.permission.READ_SETTINGS and   
com.android.launcher.permission.WRITE_SETTINGS in permission declare, not the user-permission declare.  

Now, you can run like that
![Android Oreo Launcher3](/Launcher3.png)
