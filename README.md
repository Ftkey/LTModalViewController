# LTModalViewController
LTModalViewController a easy way to display modal style controller

[![Version](https://img.shields.io/cocoapods/v/LTModalViewController.svg?style=flat)](http://cocoapods.org/pods/AlamofireRequestConfigurable)
[![Platform](https://img.shields.io/cocoapods/p/LTModalViewController.svg?style=flat)](http://cocoapods.org/pods/AlamofireRequestConfigurable)
[![Carthage compatible](https://img.shields.io/badge/LTModalViewController-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
[![License](https://img.shields.io/cocoapods/l/LTModalViewController.svg?style=flat)](http://cocoapods.org/pods/LTModalViewController)



```
    @IBAction func onAlert(sender: AnyObject) {
        let rootVc = UIStoryboard(name: "Main", bundle: nil).instantiateViewControllerWithIdentifier("ModalController")
        self.presentViewController(ModalViewController(rootController:rootVc ,contentSize:CGSizeMake(320, 200),radius:8, style:.Alert), animated: true, completion: nil)
        
    }
```
    
```
    @IBAction func onActionSheet(sender: AnyObject) {
        let rootVc = UIStoryboard(name: "Main", bundle: nil).instantiateViewControllerWithIdentifier("ModalController")
        self.presentViewController(ModalViewController(rootController:rootVc ,contentSize:CGSizeMake(320, 200), style:.ActionSheet), animated: true, completion: nil)
        
    }
```

![DEMO](https://github.com/Ftkey/LTModalViewController/raw/master/Example/DEMO.gif)