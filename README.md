# 说明

  1、配置WIFI格式为：“ssid:password:staticIP?”。例如：（SANLONG-2.4G:deng123456:192.168.1.13?）
  
  2、串口会将数据打印出来比对若正确后就可以串口"ok?"确认连接
  
  3、开始连接wifi，若成功后就会打印“WTF”
  
  4、如果wifi是正常连接的，检测端口是否有数据，若有数据，就通过UDP将数据发送出去。
  
  5、若wifi连接失败。则端口打印出MD

# 注意
  
  
  若下载编译不成功请注意开发板和库是否已经引用。
