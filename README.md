# HelloWorld
 
 @atCY1998
 
 了解Activity的生命周期
 
 当第一次运行程序时，在logcat中观察输出日志，可以发现程序启动后依次调用了onCreate()、onStart()、onResume()。当调用了onResume()方法之后程序不再向下进行，这时应用程序处于运行状态，等待与用户进行交互，运行结果如下图：
![image](https://github.com/atCY1998/HelloWorld/blob/master/images/life_one.PNG)

单机模拟器的“返回”按钮，可以看到程序退出，同时logcat中有新的日志输出。运行结果如下图：
![image](https://github.com/atCY1998/HelloWorld/blob/master/images/life_two.PNG)
