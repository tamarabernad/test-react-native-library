
# react-native-test-react-native-lib

## Getting started

`$ npm install react-native-test-react-native-lib --save`

### Mostly automatic installation

`$ react-native link react-native-test-react-native-lib`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-test-react-native-lib` and add `RNTestReactNativeLib.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNTestReactNativeLib.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNTestReactNativeLibPackage;` to the imports at the top of the file
  - Add `new RNTestReactNativeLibPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-test-react-native-lib'
  	project(':react-native-test-react-native-lib').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-test-react-native-lib/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-test-react-native-lib')
  	```


## Usage
```javascript
import RNTestReactNativeLib from 'react-native-test-react-native-lib';

// TODO: What to do with the module?
RNTestReactNativeLib;
```
  