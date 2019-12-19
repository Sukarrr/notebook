##Activity  
[lifecycle](https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=3502554975,2818731732&fm=26&gp=0.jpg)  
**关于activity的四个状态：**  
running-paused-stopped-killed  
  
1.running->当前显示在屏幕的activity(位于任务栈的顶部)，用户可见状态。  
2.paused->依旧在用户可见状态，但是界面焦点已经失去，此Activity无法与用户进行交互。  
3.stopped->用户看不到当前界面,也无法与用户进行交互 完全被覆盖.  
4.killed->当前界面被销毁，等待这系统被回收  
————————————————  
