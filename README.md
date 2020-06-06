# Plante-vs.-Zombies
自己用easyx库写出来的植物大战僵尸，由于写这个游戏的时候还没有学多态，所以虽然用到了类，但是基本上还是c语言风格

版本一的实现功能很简单，，只是实现了以下几点
：1、实现了，僵尸的hp，
  2、实现了豌豆射手的发射子弹
  3、实现了玩家的鼠标点击，选中种子卡片，进行播种，
  4、实现了僵尸hp为零的时候的删除  
  5、实现了豌豆射手被僵尸接触的时候，直接死亡，删除  
  6、实现了判断游戏失败的标志 

版本一还未实现的功能：
  1、还没有实现多植物模式（至少两种（攻击植物 + 产生太阳植物））
  2、还没有实现太阳资产的累计  
  3、还没有实现游戏菜单的设置，及很多的游戏选项卡  
  4、还没有实现游戏胜利的标志
  5、还未实现多僵尸模式



/******************************我是分割线*****************************/

版本二实现功能：
	版本二在版本一的基础上又实现了以下功能：
	 1、新增加了一个植物类，，（向日葵，也可以说是太阳花）
	 2、实现了太阳花的生成，太阳花的死亡，太阳花的贴图
	 3、僵尸的hp由原来的10增加到25，
	 4、BGM的添加，音效的导入，

版本二还没实现的功能：
	1、还没有实现太阳资产的累计  
  	2、还没有实现游戏菜单的设置，及很多的游戏选项卡  
  	3、还没有实现游戏胜利的标志
	4、还未实现多僵尸模式



/*******************************************我是分割线*******************************************/




最终版本
版本三实现功能：
	版本三在版本二的基础上又实现了以下功能：
	  1、新增加一个太阳类，
	  2、实现了玩家太阳资产机制
	  3、实现了太阳花隔一段时间产生一次太阳
	  4、实现了游戏胜利的判断，还有开始界面的贴图
	  5、实现了最后游戏失败的贴图，
