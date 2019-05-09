
# react-native-image-filter

## Getting started

`$ npm install react-native-image-filter --save`

### Mostly automatic installation

`$ react-native link react-native-image-filter`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-image-filter` and add `RNImageFilter.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNImageFilter.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNImageFilterPackage;` to the imports at the top of the file
  - Add `new RNImageFilterPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-image-filter'
  	project(':react-native-image-filter').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-image-filter/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-image-filter')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNImageFilter.sln` in `node_modules/react-native-image-filter/windows/RNImageFilter.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Image.Filter.RNImageFilter;` to the usings at the top of the file
  - Add `new RNImageFilterPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNImageFilter from 'react-native-image-filter';

// TODO: What to do with the module?
RNImageFilter;
```
  