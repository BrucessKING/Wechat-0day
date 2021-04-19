# Wechat-0day

![project](https://img.shields.io/badge/project-Wechat--0day-green )![build](https://img.shields.io/badge/build-passing-green)![language](https://img.shields.io/badge/language-JavaScript-blue)

Wechat-0day微信0day利用

#### 0x00 使用Cobalt Strike生成C#格式的32位payload

![1.png](https://i.loli.net/2021/04/19/BdzOH2KvaPs7ADk.png)

#### 0x01 将ABKing.html中的第4行的shellcode内容修改为生成的shellcode

![2.png](https://i.loli.net/2021/04/19/4yze3A9tRdLY8pb.png)

#### 0x02 使用python启动一个http服务器

```python -m http.server 80```

![3.png](https://i.loli.net/2021/04/19/5N2l6KIX837UDde.png)

#### 0x03 发送链接

![4.png](https://i.loli.net/2021/04/19/mgy7U4OB6VFXx1S.png)

#### 0x04 点击链接

![5.png](https://i.loli.net/2021/04/19/8fLHG4uRITt9pOD.png)

#### 0x05 上线

进程名确实是WeChatWeb.exe，上线成功

![6.png](https://i.loli.net/2021/04/19/IOUpqNJvAiDhl8S.png)
