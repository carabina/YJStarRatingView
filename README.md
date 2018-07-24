# YJStarRatingView
> Custom rating view.


* [Usage](#usage)
* [Installation](#installation)


&nbsp;
<img src="https://github.com/0jun0815/YJStarRatingView/blob/master/Images/yjstarratingview.gif" width="375px" height="650px"/>


&nbsp;
## Usage
### Programmatic


Initializers are as follows:
```
required init(frame: CGRect, type: RatingType = .half, isEditable: Bool = true) { ... }
convenience init(frame: CGRect, type: RatingType, isEditable: Bool, 
                 minRating: Int, maxRating: Int, currentRating: Double) { ... }
```


Example:
```
let starRatingView = YJStarRatingView(frame: frame)
starRatingView = UIImage(named: "ic_star_large")
starRatingView = UIImage(named: "ic_star_large_full")
starRatingView = UIImage(named: "ic_star_large_half")
view.addSubview(starRatingView)
```


&nbsp;
<img src="https://github.com/0jun0815/YJStarRatingView/blob/master/Images/starratingview.png" width="375px" height="650px"/>


### Interface Builder
Add a view and register the class:


<img src="https://github.com/0jun0815/YJStarRatingView/blob/master/Images/classregisteration.png" width="300px" height="300px"/>
&nbsp;


Assign a value to the properties:


<img src="https://github.com/0jun0815/YJStarRatingView/blob/master/Images/assginproperties.png" width="300px" height="230px"/>


&nbsp;
## Installation
### CocoaPods
To integrate YJStarRatingView into your Xcode project using CocoaPods, specify it in your Podfile:
```
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '10.0'
use_frameworks!

target '<Your Target Name>' do
pod 'YJStarRatingView', '~> 0.1.0'
end
```


Then, run the following command:
```
$ pod install
```


&nbsp;
&nbsp;      
### [by. 0junChoi](https://github.com/0jun0815) email: <0jun0815@gmail.com>
