实验器材:
	精英STM32F103开发板V1版本
	
实验目的:
	学习外部中断的使用
	
硬件资源:
	1,DS0(连接在PB5),DS1(连接在PE5)
	2,蜂鸣器(连接在PB8)
	3,按键KEY0(PE4)/KEY1(PE3)/KEY_UP(PA0,也称之为WK_UP)
	
实验现象:
	本实验,利用外部中断，实现与实验3类似的效果，即：通过开发板上载有的3个按
	钮（KEY_UP、KEY0和KEY1），来控制板上的2个LED（DS0和DS1）和蜂鸣器，其中
	WK_UP控制蜂鸣器，按一次叫，再按一次停；KEY1控制DS1，按一次DS1亮,再按一
	次DS1灭；KEY0则同时控制DS0和DS1，按一次，他们的状态就翻转一次。
	
注意事项:
	无.


			正点原子@ALIENTEK 
			广州市星翼电子科技有限公司
			电话：020-38271790
			传真：020-36773971
			购买：http://eboard.taobao.com
			公司网站：www.alientek.com
			技术论坛：www.openedv.com
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			