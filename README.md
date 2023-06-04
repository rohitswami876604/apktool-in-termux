![Blue Modern Motivational Podcast Youtube Thumbnail](https://github.com/rohitswami876604/apktool-in-termux/assets/120408793/d675d133-86e1-4539-969a-33579bfef18d)
To install APKTool in Termux, you can follow these steps:

1. Open the Termux app on your Android device.
2. Update the package lists by running the following command:
pkg update

3. Install the necessary dependencies by executing the command:
pkg install -y git wget

4. Download the APKTool package and wrapper script by running the command:
git clone https://github.com/rohitswami876604/apktool-in-termux.git

5. Make the downloaded file executable using the command:
chmod +x apktool.jar

6. Make the wrapper script executable with the following command:
chmod +x apktool

6. Move the APKTool file to the appropriate directory with the following command:
mv apktool $PREFIX/bin/
mv apktool.jar $PREFIX/bin/

That's it! You have successfully installed APKTool in Termux. You can now use it to decompile and recompile APK files. To verify the installation, you can run the following command to display the APKTool version:
apktool --version
