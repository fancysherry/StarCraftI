## 代码结构

 目前整体结构还比较简单，大致是个mvc结构，但可能随着游戏逻辑的复杂，兵种和地图的改造，整个结构也会不断变化，毕竟游戏的结构大多比较复杂，而简单的mvc不一定适用
 
 * packet core 是一些控制类
    *  ScreenManager 地图管理类
    *  ResourceManager 
    *  ImageManager
    *  FocusManager
    *  ...
 
 * packet net 局域网对战，udp

 * packet gui 
 
 * packet tile 各种model，兵种资源等
 * packet util   自动寻路算法等
 * packet test  程序入口     

 
 
#### 流程
 首次启动后，先加载资源对象，然后在一个死循环中不断重绘地图
 
 
#### 库
 * java swing
 * java Graphics2D