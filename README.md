# pmedia
一个简单的RTSP中继服务器，取流和发流只支持RTP over TCP方式，支持流复用。

1.编译
make

2.执行
./media 192.168.1.10 5544

3.验证
使用VLC播放rtsp://192.168.1.10:5544/rtsp://192.168.2.31:554/1
rtsp://192.168.2.31:554/1为实际的RTSP地址。