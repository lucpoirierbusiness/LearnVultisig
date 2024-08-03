# LearnVultisig
Install VultisigApp on windows or Linux
Hopefully you already installed the Vultsig app on your iphone or android phone. If on iphone you will need to install testflight. First go to the App Store and search testflight the rest is straightforward.
After you've installed the app on one device you will need a second device to use the wallet. I spent ages trying to configure my computer to run the google play package or the github package. Maybe someone can, but not me. I went through this process cause right now you can only install on a mac, iOS or android. I only have windows or linux computers. So these instructions runs an app as if you have an android device.
1) Get Android Studio from https://developer.android.com/studio
2) Installing on windows is straightforward. On Linux a little harder, but I'm an absolute beginner so if I can do it so can you
   a) LINUX ONLY - make a directory where you want to install is for simplicity: mkdir -p /home/lucp/d/android-studio
   b) Navigate to where you downloaded the tar file for android-studio. I used cd ~/Downloads
   c) Unpack the files: tar -xzf android-studio-2024.1.1.12-linux.tar.gz -C ~/android-studio
   d) (Optional) Make it so you can run the package from anywhere: export PATH=$PATH:/home/lucp/d/android-studio/bin
   e) Run android-studio: cd ~/android-studio/bin ./studio.sh (unless you did step d then just type ./studio.sh from anywhere)
   f) Here things got weird for me cause I'm not a developer and never done anything like this, but easiest way is to just run the "Pixel Fold API" if your android-studio has that option.
   g) If you don't have the option to just run an existing virtual image create one.
   h) From here it took me a while but just keep trying until you can open the google play store.
   i) Search vultisig or go to https://play.google.com/store/apps/details?id=com.vultisig.wallet&pli=1
   f) Once installed you will be able to run the Vultisig wallet and get yourself set up.

I hope this helps anyone whose a novice like me and just wants to learn how this works as the dev experts get up and running with the real work. Meanwhile I'm sure they will release a windows and other versions of the app soon so multi signature security can become your normal method of operating.




