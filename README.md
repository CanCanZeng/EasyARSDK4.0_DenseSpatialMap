This is a sample project from EasyAR(www.easyar.cn) to show the ability of reconstructing the environment on a mobile phone in real-time.

![image](https://github.com/CanCanZeng/EasyARSDK4.0_DenseSpatialMap/blob/master/sample.gif)

The original project I use is EasyARSenseUnityPlugin_4.0.0-final_UnityPlugin_Samples.zip  from https://www.easyar.cn/view/download.html, but the produced project is too large for uploading to Github, I just upload the APK for the community to evaluate the result on Android phone.

Please note that not all android phones are supported, since it requires motion tracking result as it’s input, only devices that are supported by EasyAR motion tracking module, ARKit or ARCore are able to run this project. 

There is also a sample shows how to create a custom camera in EasyAR SDK, maybe you can just implement your own camera device to provide the image and pose, so that the DenseSpatialMap module can produce a normal reconstruction result.
