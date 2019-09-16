# Problems

## Boot

### 插HDMI+DVI屏幕,不启动
- 已知
  - CPU:E3V3,GPU:GTX1070
  - DVI: AOC 1080P, HDMI: Pilips 2K
  - 正常开机率85%


- 表现:
  - 正常开机读条正常速度到一半.苹果消失,进度条停止不动
  - 开机-V(-v,排除PS/2,Lilu,AppleALC)滚动显示完存储cpu硬件之后;屏幕中间1/3自负消失,卡死;
  - 拔掉HDMI,只插DVI正常;开机成功后链接HDMI,正常(运行,显示,声音)

- 后续:
  - 尝试关闭HDMI显示器,而不完全拔出开机