### Description

This is an experimental fork of [AwesomeMenu](https://github.com/levey/AwesomeMenu) from [@LeveyZhu](https://twitter.com/#!/LeveyZhu) which enables the possibility to add the AwesomeMenu to any `UIControl`. 

The setup is pretty simple (please check [AwesomeMenu](https://github.com/levey/AwesomeMenu), if you want to know how to setup a menu itself):

	//create a custom control
    UIButton *btn = [[UIButton alloc] initWithFrame:CGRectMake(130, 200, 60, 60)];
    btn.backgroundColor = [UIColor greenColor];
    [btn setShowsTouchWhenHighlighted:YES];
    
    //important add the control to the superview before you add the menu
    [self.window addSubview:btn];

    //register the control at the menu
    [_menu registerCenterButton:btn];


### Further informations and license
- Check the [original repo](https://github.com/levey/AwesomeMenu) for informations which aren't on this page. 
- Follow [@gekitz](http://twitter.com/gekitz)

