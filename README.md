# Installation-Procedure
# INSTALLING AND RUNNING APPLICATIONS ON ANDROID STUDIO DATE
Step 1 - System Requirements 

The required tools to develop Android applications are open source and can be downloaded from the 
Web. Following is the list of software you will need before you start your Android application 
programming. 
Java JDK5 or later version 
Java Runtime Environment (JRE) 
6Android Studio 
 
Step 2 - Setup Android Studio 
 
Android Studio is the official IDE for android application development.It works based on IntelliJ 
IDEA, You can download the latest version of android studio from Android Studio 2.2 Download, If 
you are new to installing Android Studio on windows,you will find a file, which is named 
as android-studio-bundle-143.3101438-windows.exe.So just download and run on windows machine 
according to android studio wizard guideline. 
If you are installing Android Studio on Mac or Linux, You can download the latest version from 
Android Studio Mac Download,or Android Studio Linux Download, check the instructions provided 
along with the downloaded file for Mac OS and Linux. This tutorial will consider that you are going 
to setup your environment on Windows machine having Windows 8.1 operating system. Installation 
So let's launch Android Studio.exe,Make sure before launch Android Studio, Our Machine should 
required installed Java JDK. To install Java JDK,take a references of Android environment setup

![Screenshot 2024-11-20 021400](https://github.com/user-attachments/assets/00abcdf0-0a8e-4079-8e8b-f06d65167b88)

Once you launched Android Studio, its time to mention JDK7 path or later version in androidstudio installer. 

![Screenshot 2024-11-20 021642](https://github.com/user-attachments/assets/9f19ffb9-4512-4b39-b1a5-48c79333f758)


Below the image initiating JDK to android SDK

![Screenshot 2024-11-20 021721](https://github.com/user-attachments/assets/43eb8052-2c19-41f4-b700-c7d629e1dd7e)


Need to check the components, which are required to create applications, below the image has selected Android Studio, Android SDK, Android Virtual Machine and performance(Intel chip).

![Screenshot 2024-11-20 021816](https://github.com/user-attachments/assets/22c96e55-ef8f-4798-9457-03759d38e8f1)


Need to specify the location of local machine path for Android studio and Android SDK, below the image has taken default location of windows 8.1 x64 bit architecture. 

![Screenshot 2024-11-20 021902](https://github.com/user-attachments/assets/d65dcb46-5f72-4574-a8e0-c46486ba0442)

Need to specify the ram space for Android emulator by default it would take 512MB of localmachine RAM.

![Screenshot 2024-11-20 021937](https://github.com/user-attachments/assets/32d3f573-0d7b-4469-80d1-8e8a6cdb2c12)

At final stage, it would extract SDK packages into our local machine, it would take a while time to finish the task and would take 2626MB of Hard disk space. 

![Screenshot 2024-11-20 022041](https://github.com/user-attachments/assets/dbdea4eb-b7ef-47b0-874c-1a6c4834c775)

After done all above steps perfectly, you must get finish button and it gonna be open androidstudio project with Welcome to android studio message as shown below

![Screenshot 2024-11-20 022128](https://github.com/user-attachments/assets/80570bd0-f9b3-47d7-9f46-007a081b8f0e)

You can start your application development by calling start a new android studio project. in a new installation frame should ask Application name, package information and location of the project. 

![Screenshot 2024-11-20 022211](https://github.com/user-attachments/assets/7cd88612-572a-4af7-abaf-099baae9db04)

After entered application name, it going to be called select the form factors your application runson, here need to specify Minimum SDK, in our tutorial, I have declared as API23: Android 
6.0(Mashmallow)

![Screenshot 2024-11-20 022306](https://github.com/user-attachments/assets/00cc08fe-fcab-475c-beef-e12cad593e52)


The next level of installation should contain selecting the activity to mobile, it specifies the default layout for Applications

![Screenshot 2024-11-20 022359](https://github.com/user-attachments/assets/e230a251-e058-495b-adb8-c7fead27afdc)

At the final stage it going to be open development tool to write the application code.

![Screenshot 2024-11-20 022434](https://github.com/user-attachments/assets/b6b35a51-0f05-4041-9d28-ddec295834df)

Step 3 - Create Android Virtual Device 
To test your Android applications, you will need a virtual Android device. So before we start writing our code, let us create an Android virtual device. Launch Android AVD Manager Clicking 
AVD_Manager icon as shown below

![Screenshot 2024-11-20 022512](https://github.com/user-attachments/assets/e38881e6-95d3-4fa7-a2d6-bc6205134521)

After Click on a virtual device icon, it going to be shown by default virtual devices which are 
present on your SDK, or else need to create a virtual device by clicking Create new Virtual 
device button


![Screenshot 2024-11-20 022546](https://github.com/user-attachments/assets/5bdd52bd-9c41-4002-b6db-7872a0ae4291)

If your AVD is created successfully it means your environment is ready for Android application 
development. If you like, you can close this window using top-right cross button. Better you re- start your machine and once you are done with this last step, you are ready to proceed for your first Android example but before that we will see few more important concepts related to AndroidApplication Development.
