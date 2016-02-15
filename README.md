# SunnyFPS v0.0.1

###本工程用于显示UIKit FPS数值

####Installation with CocoaPods

####Podfile

	pod "SunnyFPS"


####使用：

didFinishLaunchingWithOptions 中添加如下：

	#if DEBUG
    let fpsLabel =SunnyFPS(frame:CGRectMake(15,SCREEN_HEIGHT-40, 55, 20));
    self.window?.addSubview(fpsLabel);
    #else
	#endif





###欢迎大家 issue


