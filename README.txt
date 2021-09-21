https://www.trufflesuite.com/boxes/drizzle-react-native
https://reactnative.dev/docs/getting-started

$ curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
$ echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
$ sudo apt update
$ sudo apt install yarn
$ yarn --version
1.22.5
$ npm install --save-dev sha3
$ npm install --save-dev script
$ sudo npm install -g react-native-cli
$ npm add @babel/runtime
$ npm install
$ truffle unbox drizzle-react-native
$ truffle unbox drizzle  
$ truffle compile
$ truffle migrate
$ npm run start


$ cat ~/.profile
# Android SDK
export ANDROID_HOME="$HOME/Apps/Android_SDK/Sdk"
export PATH=$PATH:$ANDROID_HOME/emulator:$ANDROID_HOME/tools:$ANDROID_HOME/tools/bin:$ANDROID_HOME/platform-tools
$ react-native doctor
$ react-native start
$ emulator -avd Pixel_4_XL_API_29 -port 5557
$ adb -s emulator-5557 reverse tcp:8545 tcp:8545
$ react-native run-android --deviceId emulator-5557 --verbose


