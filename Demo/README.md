# WebView Component

I will be following along with the [tutorial](https://reactnative.dev/docs/fabric-native-components-introduction) provided by the React Native docs on how to create a Fabric Native Component. I will only be following the tutorial for creating an iOS component.

Step 1: I generated a demo app that I will use to test the WebView component we will be creating.

Step 2: I created an additional `specs` folder where I can define the Codegen's specifications.

Step 3: I created the `WebViewNativeComponent.ts` file in the `specs` folder. This is where we will define the native component's properties and methods.

Step 4: I created the `RCTWebView.h` and `RCTWebView.mm` files in the `ios/WebView` folder. These are the native implementation of the WebView component. I then linked the native implementation in the `AppDelegate.mm` file using the `thirdPartyFabricComponents` dictionary.

Step 5: I added the WebView component to the `App.tsx` file so that I can test it.
