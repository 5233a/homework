# HTML5游戏的策划与设计（绝对原创，纯手打）
## 游戏策划
### 创作动机（Creative Motivation）
   在经过游戏教程学习了HTML5游戏制作后，跃跃欲试，准备自己做出一个简易而又有趣的小游戏。
### 目标市场（Targeted Market）
   该游戏为自制娱乐练习，无目标市场。
### 楔子（Setting）
   很久很久以前，有一个强壮的战士，由于实力超群，他逐渐积累声望，并受到了国王的赏识，他立下了赫赫战功，为国家的安定做出了汗马功劳，在最后一场战争结束  
   后，国家实现了统一。这天晚上，国王邀请他参加盛宴，宴会上当战士喝下国王赐下的美酒后，突然全身出血倒地，这时战士才发现了国王邪恶的本质。为了复仇，战士 
   与死神签订了邪恶的契约，他在死神的帮助下复活，不过成为了一个丑陋的怪物（monster），国王立即派遣士兵去追杀它。战士能否逃脱士兵的追击，逃离城堡呢？   
### 玩法（Gameplay）
   玩家击败所有士兵或到达出口任务完成。玩家无法到达出口任务失败。玩家使用键盘方向键来控制战士移动，目前具有少数特殊能力，可以二段跳，玩家接触士兵并且位
   于士兵正上方可以发动死亡践踏消灭士兵，否则会发动圣光庇护全身闪光而避免受伤。
### 人设与道具（Game Sprites）
 1. Player ： 战士（Monster）。与死神签订条约后，战士的能力得到了强化，他有无限的体力，并有死亡践踏和圣光守护以及二段跳三种能力。
 2. Enemies ： 士兵（Soldiers）。士兵具有巡逻的能力，他们分布广泛，四处巡逻，有条不紊，生命力极强，只有死亡践踏才能消灭他们。
## 游戏设计
### Object（事物）：战士
   1. Attributes（属性）：图片，位置
   2. Collaborator（合作者）：精灵
   3. Events & Actions（事件及行为）移动，键盘方向键（On every tick）
   4. 死亡践踏（从正上方踩到士兵），士兵被消灭
   5. 神圣闪光（没从正上方，但接触到了士兵），战士闪光但士兵不被消灭
   6. 死亡（战士掉落），战士被消灭
### Object(事物)：士兵
   1. Attributes（属性）：图片，位置
   2. Collaborator（合作者）：无
   3. Events & Actions(事件及行为)：碰撞，反弹


![效果演示](https://imgsa.baidu.com/forum/w%3D580/sign=d0336942b7a1cd1105b672288913c8b0/53a93c355982b2b7f84db4b63cadcbef74099be5.jpg)
