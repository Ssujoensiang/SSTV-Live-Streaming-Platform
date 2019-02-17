# nginx-rtmp-win32

Nginx: 1.12.1  
Nginx-Rtmp-Module: 1.2.0  
openssl-1.0.2l  
pcre-8.40  
zlib-1.2.11

# 使用方法
双击nginx.exe
# 简要说明
内置了rtmp与hls两套直播方案
rtmp时间延迟在3s左右
hls延迟在15s左右，但允许用户在手机播放
内置了播放页，需要flash player播放器支持

# 使用前配置
打开目录下 html文件夹
用“写字板”打开 index.html，更改里面提示的ip为当前本机ip
用“写字板”打开 play.html，更改里面提示的直播流地址为本机的直播流地址

查看ip的方式: 打开开始菜单->输入cmd->回车->输入"ipconfig"（不留引号）->看 ipv4地址
直播流格式：rtmp://你的ip地址:1935/live/流名称 (上次我们设置的流名称是在obs里的2333 修改后记得对应参数）

# 2.16更新
修复了中文路径无法启动nginx.exe的bug
使用时请在完全英文路径的文件夹运行


