# Issues

### How to change minimum android version?

Go to Build &gt; General and change the version.

**Source** : [https://forums.xamarin.com/discussion/31147/how-to-change-minimum-android-version](https://forums.xamarin.com/discussion/31147/how-to-change-minimum-android-version)

### How to solve target framework issue ?

You must build and target API 23/24/25. You can set your minimum lower through , for instance:![](/assets/targetsdk.png)

**Source**: [https://github.com/jamesmontemagno/GeolocatorPlugin/issues/21](https://github.com/jamesmontemagno/GeolocatorPlugin/issues/21)

If you still have the problem you have to install the SDK of the last or indicated target in Visual Studio.

### **My project only works with version 7.1. **

First of all, you have to set up the project as shown in the image above. However, since I recently installed Visual Studio and started using Xamarin, my project works just with the version 7.1. I don´t know yet how to be able to run it with lower version since I getting the error showed below.

![](/assets/errorVersion.png)

It is important to have in mind that if using a virtual device, you have to match it with the setup version, otherwise it will crash. Additionally, the set up I´m using is the following.![](/assets/setup.png)

In summary, I will be just using the version 7.1 for setup and virtual device. 

