## Android Development Immersive Installation Instructions

Hello future Android Developers!
We here at General Assembly are super excited to start working with you! 
Just as a matter of housekeeping, there are a few things we’d like you to install on your computers before the class starts so we can hit the ground running on the first day.

#### 1. Java Development Kit ( JDK )

First, you need to install Java Development Kit if you haven’t done so already. Go to [this link](http://www.oracle.com/technetwork/java/javase/downloads/index.html) and click on Downloads (see the picture below). 

Include image
![]()

There, select your operating system (if you’re on a Mac, it would be Mac OS X x64), and make sure to accept the terms & agreements. Then just open the `.dmg` file and follow the installation steps. 

Once you finished that, check to make sure it’s downloaded by opening the terminal application on your computer (you can find this by searching for terminal using Spotlight (command space!) on your Mac). Once terminal has loaded, type in `java -version` and hit enter. Java version should have popped up as 1.8 or greater, which means you did it! If not, try going back to step one and just do it all again.


#### 2. IntelliJ IDE

We want you to set up IntelliJ, a development environment for Java. Follow the [download instructions](https://www.jetbrains.com/idea/). 


#### 3. Android Studio

Next, you need to install and set up Android Studio + SDK. Head over [here](http://developer.android.com/sdk/index.html), agree to the Terms & Conditions, launch that `.dmg` file, and drag and drop Android Studio into your applications. We still need to set it up, so open it up and go through the steps. You should be able to click next on the welcome screen and Java settings, choose Standard for the install type, and accept the SDK License and intel-android-extra-license, click finish, and just wait for the downloads to complete!

#### 4. Genymotion

In addition to Android Studio, we’re going to be using an emulating software called Genymotion to help us run our Android applications on our computers. It is free for personal use, so [create your account](https://www.genymotion.com/account/create/). For company size, choose Personal Use, and for Usage type choose Training. Fill out the rest of the form and you should receive an e-mail with a confirmation link,  and it should send you to a landing page. Click continue, then choose a plan, and select the individual tab. Choose the basic plan by selecting get started, and you will be given a download link for your device. Download it, and open the .dmg. Complete the instillation, and make sure to drag both items into your application folder!


#### 5. VirtualBox

If you try and open Genymotion now, it will give you an error message and stop working. This is because Genymotion requires ANOTHER piece of software, VirtualBox, so now head over to their [website](https://www.virtualbox.org/wiki/Downloads) and click the and64 link to the right of your operating system (see the image below circling what to click). 

Include image
![]()

Now open the `.dmg` file and run the `.pkg`. Follow the installation instructions, and then open the application. Now try and open your Genymotion! It should work.


#### 6. Link Genymotion and Android Studio

There is one last thing to do: Link your Genymotion with your Android Studio. Open it up and go to `Android Studio -> Preferences`.  From there, go to the plugin tab on the left. and click browse repositories. It might be faded out at first, but don’t worry! From there, type in Genymotion in the top search bar and select the item in the list below. On the right you will see a description with a green install button. Click it. Install the plugin and when it changes to a restart Android Studio button, click that. 

Once your Android Studio has restarted, you should see a new button on the top of your toolbar, as seen in the picture below:

Include Image
![]()

Click it. It might open a prompt for you to enter the path to your Genymotion app, which you should be able to find in your Applications folder if you dragged it in there before when installing it. Select the Genymotion App, and hit the blue button to confirm. Your Genymotion should now be connected and you can start making and running virtual machines in it through your Android Developer Studio!

#### 7. Xcode

The last thing you need to do is install Xcode for some  command line tools. You can find it in the app store and download it. It is a lengthy download, but a one-time thing. Make sure you go through the whole setup. Make sure you open it once!

Include image
![]()
