# 前言
本人仅作简中化，不对代码做任何修改。此模组由「隨風飄逸」制作，以下是原项目链接[DOL_Baileys_piggy_banks](https://github.com/chris81605/Degrees-of-Lewdity_Baileys_piggy_banks)
# 贝利的小金库  
**在贝利办公室、家中新增 “贝利的小金库”，PC可于特定时段去尝试撬开它爆贝利金币。**  
# 更新日志
## 0.2.1  
1.修复问题  
* (1)修复已经清空贝利小金库后离开场景再进入后 
"**拿走金库里的钱**" 选项依然存在导致可能让贝利存款及玩家存款数值异常的问题  
* (2)不幸触发问题可透过 **回档** 或：  
	* 言灵：<<link [[修复|$passage]]>><<unset $money>><<set $money to `任意不小于值100`>><<unset $Baileys_money>><<\/link>>修复  
	* 需使用新版解除言灵限制的言灵系统
 	* `任意不小于值100` 请填入任意 **大于** `100`的数值
  
## 0.2.0  
1.优化代码结构，將计算与判断代码独立至"**Widgets Bailey's piggy_banks**"，方便后续调用
* (1)为未来的剧情做准备，将可能不会用到的计算做成Widgets

## 0.1.2
1.修复刚开新档就去撬贝利小金库导致贝利存款初始化为0的问题
* (1)修复问题
* (2)初始化计算方式变更
2.修复贝利存款为0导致可能发生的潜在问题

* (1)修复问题
* (2)调整条件判断代码(至少能给贝利留下￡10 XD
3.调整部分文字显示
* (1)扫空贝利金库收穫描述，增加新的级距

### 0.1.1  
1.修复无限刷诡术问题

### 0.1.0
1.基础爆金币功能完成  
* (1)各项数值待优化  

# todo  
✔️在贝利办公室新增 “贝利的小金库”  
  在贝利家新增贝利的金库  
✔️pc于特定时间(半夜)可进入办公室尝试撬开保险箱  
✔️新增贝利的存款机制，小金库内可获取的金币数量基于贝利的存款。  
  当贝利存款金额低于特定金额，当週贝利保护费加倍。  
✔️保险箱上锁难度随机(简单->非常困难 or 密码锁小游戏？)  
✔️可取得金币数量随机(与贝利存款挂勾)  
  新增事件，撬金库被贝利发现  
 群友的点子：   
    新增贝利的电脑可黑客入侵转走被利银行帐户的钱  
    白天也可以去撬小金库，但被发现的机率大增，当贝利爱情足够高时可以当贝利的面前撬，然后贝利笑著看你撬金库后狠狠的撅你。  
    撬孤儿院的贝利小金库可能被贝利发现，被发现后会被贝利撅(增加贝利的爱情程度)  
    撬贝利家的小金库可能被贝利发现，发现后会被贝利卖掉，爱情足够高则被留下来当RBQ。(可选择)  
    变成贝利的RBQ后，贝利每晚会尝试将在外游荡的PC抓回家撅。  
    变成贝利的RBQ后，可以请贝利带你去镇上的任何地方。  
