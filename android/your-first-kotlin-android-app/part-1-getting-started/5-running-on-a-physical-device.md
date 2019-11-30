# 5 - Running on a Physical Device

We now have our application running in a virtual device.  Now, testing on a virtual device is great and all.  However, there is no substitute for testing our app on a physical device.

Every now and then, it is good to run your app on an actual device to make sure it is still running correctly.  For this episode, you'll need an Android device connected to your computer via USB.

We'll need to enable Developer mode on your device before we can run or debug your app on the device. Let's take a look at how we do that now.

Turn on the device and go to Settings. The exact process here will change slightly between different phones and versions of Android, but the basic steps should remain the same. Next, scroll all the way down and select About phone. Scroll to the Build number and tap it multiple times. It'll eventually tell you to keep tapping to become a developer.  Keep tapping until you get a successful message that you are a developer. Go back to Settings and look for Developer options and select it.

Turn on the USB debugging switch. Then connect your device to your computer with USB. Your phone will prompt you with a dialog to allow USB debugging. If this is your computer, feel free to check the Always allow from this computer option so that you no longer get this message each time you plug in your phone.

Your device is now ready to test your app. Back in Android Studio, click on the Run button. In the Development Target window, you should now see the device plugged in as a possible target for running. Select your device, then click OK. You should now see the app running on your device.

