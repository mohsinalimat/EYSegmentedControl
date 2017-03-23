EYSegmentedControl
==================

Custom segmented control written in swift 3.  
Fully customisable.  

Demo
----
To add
![Demo](https://gfycat.com/ifr/UncomfortableObviousAustralianfurseal.gif)
<div style='position:relative; padding-bottom:178%'><iframe src='https://gfycat.com/ifr/UncomfortableObviousAustralianfurseal' frameborder='0' scrolling='no' width='100%' height='100%' style='position:absolute;top:0;left:0;' allowfullscreen></iframe></div>

Install
-------

##### Manual

Copy & paste `CustomSegmentedControl.swift` in your project

##### CocoaPods

``` ruby
To add
```

Usage
-----

Drag a `UIView` into your storyboard! Change the class to `CustomSegmentedControl`. The view will be updated! 


### Edit / Add / Remove Labels according to preference!

``` swift
  var items : [String] = ["Item1", "Item2"] 
```
### In storyboard Edit the following properties! 

##### For the UIView
Background Color. 
Corner Radius.

##### For all Labels
Unselected Labels Color.
Highlighted Label Color.

##### For the Highlighted Label
Selected Label Background Color.
Selected Label Border Width.
Selected Label Border Color. 

### Create an Outlet for the Control! 

``` swift
    @IBOutlet weak var segmented: CustomSegmentedControl! 
```

### Create a Target for your Outlet! 

``` swift
    func segmentedViewControllerValueChanged(_ sender: Any){
    //Logic goes here and is based on index selection
    }

```

### Add your Target 

``` swift
  segmented.addTarget(self, action: #selector(ViewController.segmentedViewControllerValueChanged(_:)), for: .valueChanged)
```

And that is it.

``` swift
 to add
```

To add: 

``` swift
//to add
```
