# 使用Java制作的坦克大战(可双人连击合作)
只是服务器端，搭配[客户端](https://github.com/13535944743/TankClient/)使用

技术要点：
  1. Java的用户界面(GUI)
  2. 碰撞检测(构建两个矩形，检测有无相交)
    ![](https://pic.imgdb.cn/item/61594f9f2ab3f51d91b46f5a.jpg)
  3. Java多线程、网络编程
  4. 字符串拼接方法，通过规定好的规则收发信息(可能优点自定义协议的意思)
    例子：发送e@95@31@1意思：e代表enemy，@是用来分割信息，95代表横坐标，31代表纵坐标，1代表坦克id