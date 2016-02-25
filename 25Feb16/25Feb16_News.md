News
====

## Chapter 0. What's up?

* Sharp reportedly accepts $6.25B takeover bid from Foxconn

[_More_ appleinsider.com](http://appleinsider.com/articles/16/02/24/sharp-reportedly-accepts-625b-foxconn-takeover-bid)


* Microsoft Acquires Xamarin 

[_More_ weblogs.asp.net](http://weblogs.asp.net/scottgu/welcoming-the-xamarin-team-to-microsoft)


* Apple Pay become available in China 

[_More_ engadget.com](http://www.engadget.com/2016/02/16/apple-pay-china-launch/)


***



## Chapter 1. Environment

##### GitHub 

* made support of markdown based templates for Contribution, Issues and Pull Requests 
	+ `CONTRIBUTING.md` `ISSUE_TEMPLATE.md` `PULL_REQUEST_TEMPLATE.md`
	+  Add files to: `./github`

[_More_ github.com](https://github.com/blog/2111-issue-and-pull-request-templates)

***



## Chapter 2. Xcode 7.3

* Code completion provides better matches with fewer keystrokes
	+ ... and makes it easier to find what you’re looking for.

	+ Typing "myDelegate.tveh”, where myDelegate is a UITableViewDelegate, gives tableView(_ tableView: UITableView, estimatedHeightForRowAtIndexPath indexPath: NSIndexPath) -> CGFloat as the first completion.

 	+ Typing “myView.color”, where myView is a UIView, gives every property containing the “color” substring, like “tintColor” and “backgroundColor”. 

* Swift 2.2 support 

* Swift version check, starting Xcode 7.3 beta 4.
```swift
#if swift(>=2.2)  
	print(“Hello!”) 
#elseif swift(1.0) 
	println(“Hello!”)  
#else

#endif
```

[_More_](http://adcdownload.apple.com/Developer_Tools/Xcode_7.3_beta_4/Xcode_7.3_beta_4_Release_Notes.pdf)

***



## Chapter 3. iOS 9.3 changelog

* UIUserInterfaceIdiomCarPlay


* WatchConnectivityFramework `more than one device support` + changes in API 
	
	+ iOS 9.3 supports pairing iPhones with multiple watches running watchOS 2.2. To choose the Apple Watch that your iPhone connects to, use the Watch app on your iPhone. To create, pair, and switch between simulated Apple Watches, use the Devices window in Xcode. 

[_More_](https://developer.apple.com/library/prerelease/ios/documentation/WatchConnectivity/Reference/WCSession_class/index.html#//apple_ref/doc/uid/TP40015237-CH1-SW56)


* HealthKitUI -> HKActivityRingView 

[_More_](https://developer.apple.com/library/prerelease/ios/documentation/HealthKitUI/Reference/HKActivityRingView_Class/index.html#//apple_ref/occ/cl/HKActivityRingView)

***


## Chapter 4. Apple TV

* Apple Developer Tech Talks available:

[_More_ developer.apple.com](https://developer.apple.com/videos/techtalks-apple-tv/)

***


## Chapter 5. Swift

* IBM Watson API with Swift iOS SDK 

[_More_](https://developer.ibm.com/swift/2015/12/18/introducing-the-new-watson-sdk-for-ios-beta/)


* Vapor : web-server on Swift 

[_More_](https://github.com/qutheory/vapor)

***


## Chapter 6. Links

* IBM Swift Blog 

[_More_](https://developer.ibm.com/swift)


* Swift Evolution 

[_More_](https://github.com/apple/swift-evolution)

* Y Combinator News Feed 

[_More_](https://news.ycombinator.com/news)






