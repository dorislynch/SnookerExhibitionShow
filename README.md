
# react-native-snooker-exhibition-show

## Getting started

`$ npm install react-native-snooker-exhibition-show --save`

### Mostly automatic installation

`$ react-native link react-native-snooker-exhibition-show`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-snooker-exhibition-show` and add `RNSnookerExhibitionShow.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNSnookerExhibitionShow.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNSnookerExhibitionShowPackage;` to the imports at the top of the file
  - Add `new RNSnookerExhibitionShowPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-snooker-exhibition-show'
  	project(':react-native-snooker-exhibition-show').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-snooker-exhibition-show/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-snooker-exhibition-show')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNSnookerExhibitionShow.sln` in `node_modules/react-native-snooker-exhibition-show/windows/RNSnookerExhibitionShow.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Snooker.Exhibition.Show.RNSnookerExhibitionShow;` to the usings at the top of the file
  - Add `new RNSnookerExhibitionShowPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNSnookerExhibitionShow from 'react-native-snooker-exhibition-show';

// TODO: What to do with the module?
RNSnookerExhibitionShow;
```
  