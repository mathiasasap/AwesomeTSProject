# AwesomeTSProject
React native demo project of the [official react native documentation](https://facebook.github.io/react-native/docs/0.60/getting-started)

# Dependencies

1. Android Studio (to emulate android device)
1. Npx module

# Before starting

On Ubuntu, you can add Android SDK to your PATH by adding the following lines to the ~/.bash_profile or ~/.bashrc configuration files:

```
export ANDROID_HOME=$HOME/Android/Sdk
export PATH=$PATH:$ANDROID_HOME/emulator
export PATH=$PATH:$ANDROID_HOME/tools
export PATH=$PATH:$ANDROID_HOME/tools/bin
export PATH=$PATH:$ANDROID_HOME/platform-tools
```
We also added the tools/bin and platform-tools folder to the PATH variable to be able to run various utilities like adb from any folder. Next, run the following command:

`source ~/.bashrc` or `source ~/.bash_profile` 

# Getting started
1. Clone the project
1. Run react native project with the command `npx react-native start`
1. Run the android project with the command `npx react-native run-android`