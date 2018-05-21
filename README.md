# Fight_against_landlords
斗地主游戏
这个项目是与两位好友一起做的一个斗地主小游戏项目，利用纯HTML5+CSS3+Jquery来完成这个项目，这个项目有开场动画，发牌动画，背景视频，出牌的音效，牌型判断，以及AI出牌和AI提示等功能。
项目的开场动画和发牌动画都是利用CSS3的动画属性和jquery的动画属性做出来的，难点在于54张按设定的步骤运动，所以用jquery动画属性来控制这54张牌的运动轨迹，背景视频就是简单利用了CSS3的Z-index属性把视频放在了最底层，出牌的音效与牌型的判断是集合在一起的，当牌型判断完之后就判断该出现的音效，例如王炸就会出现王炸的动画与音效。20张牌以内的所有可能出现的牌型都在算法里面，保证了在运行的时候不会出现逻辑的BUG。AI出牌与提示功能就厉害了，获取桌面上的牌的点数，进行与手牌的对比，先判断牌型的点数，牌型的张数与牌型的花色，如果手牌不能出的话就提示没有牌出，如果有的话就会把可出的牌向上移动一小段距离，在按一次提示的话就会把下一种可出的牌移动，同时收起第一种牌型。
