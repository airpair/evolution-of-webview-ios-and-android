## 1 What is a Hybrid Mobile App?

With the advent of new mobile platforms, it has become very difficult for Mobile Developers to create Mobile Apps which work seamlessly across all platforms like IOS, Android, Windows, FirefoxOS, Blackberry etc. Hybrid Mobile App is the solution to this problem by enabling developers use popular web technologies like HTML5, CSS & Javascript to create apps for all these platforms using a single codebase. Hybrid Mobile App is built using mix of native & web technologies.

## 2 What is the role of WebView in a Hybrid Mobile App ?

WebView is a generic name given to the browser like control available in any native mobile platform toolsets to load web content in a native app. Developers have been exploiting this component to create hybrid mobile apps, which is loading web content locally or from a remote server imitating Mobile UI components using HTML & CSS. In general WebView have capability of injecting dynamic HTML content, Javascript code or CSS styles to the web content loaded in it.

<img src='http://appsonmob.com/wp-content/uploads/2014/11/Screen-Shot-2014-11-21-at-5.39.55-pm-300x153.png'>

 ## 3 Evolution of WebView Controls in IOS & Android? 

Performance of a Hybrid App is largely dependent on the WebView control as it responsible for UI Rendering & running Javascript code of the app using its embedded javascript engine. Generally, in iOS & Android both earlier the WebView control did not use the latest and updated rendering/javascript engines used by the native browsers – Safari & Chrome in IOS & Android respectively. Hence, the performance of Safari & Chrome was much better than any of the Hybrid App. Facebook had once fallen for this shortcoming and had to rewrite their previously written hybrid app to a completely native app.

Apple recently introduced new WKWebView API in iOS 8 which leverages the Nitro Javascript JIT compiler used by Safari earlier. It will surely increase the performance of javascript execution in Hybrid Apps by more than 300% according to most of the benchmarks. Nitro compiles the Javascript into native code which makes it faster than the older UIWebView control. It will not have any effect on the UI Layer rendering and accessing hardware acceleration but still can affect the performance of apps using a lot of javascript execution.

Google also had a separate WebView control in their native toolset which had different runtime engine from the Chromium open source browser till Android 4.4. From Android Kitkat 4.4, it announced that the WebView control will be based on the open source Chromium project. With the release of Android 5 Lollipop Google has released Updatable WebViews which would enable users to get updates for WebView independently directly from play store. This would be very helpful to receive performance enhancements and security upgrade patches.

## 4 Benefits of the latest WebView controls in IOS & Android 

Hybrid Apps were seen as third class citizens in the mobile app community till now. But after all these updates, the performance of Hybrid Apps will be significantly better and we can envisage a future of single codebase for multiple platforms. The html5 developers would be able to create engaging user experiences on the mobile and for multiple screen sizes and device types.