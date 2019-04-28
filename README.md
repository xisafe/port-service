# port-service
常见TCP/UDP端口所对应的服务
IANA(Internet Assigned Numbers Authority)把端口号分为三类：已知的, 已注册的及动态和(或)专用端口.

        0-1023: 由IANA控制, 为已知服务所保留

        1024-49151: 由IANA列出的已注册的端口,由普通用户执行的普通用户进程或程序可以使用这些端口.

        49152-65535: 动态和(或)专用端口.

普通用户应用程序应在1024-49151范围内选用已注册的端口,以避免可能使用其他应用程序或系统服务正在使用的端口.

下面地址上列举了IANA规定的端口对应的协议和服务, 如果需要详细内容, 请参考:

http://www.iana.org/assignments/service-names-port-numbers/service-names-port-numbers.xml
