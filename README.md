# skillsForDev
开发过程中小技巧
1.windows杀死被某个端口占用的进程：
  * 找出进程id：netstat -aon|findstr "7070" ；
  * 强杀进程：taskkill /pid 17020 /f  ；
