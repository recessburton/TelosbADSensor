Author:YTC 
Mail:recessburton@gmail.com
Created Time: 2015.3.25

Description：
	TinyOS TelosB AD扩展口接收传感器数据的封装程序.
	此程序包括TelosbADSensor接口和两个组件:ADSensorP和ADSensorC.
	接口为用户提供命令readAD(),用户只需实现readADDone事件即可.
	该AD采集接口的默认的AD参数如下：
	通道：A0口
	参考电压：2.5V
	更多详细参数见ADSensorP.nc文件.
	
Known Bugs: 
		none.

