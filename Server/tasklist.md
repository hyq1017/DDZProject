###基础库
- 定时器
- 前后端通信协议--sproto
- redis服务器搭建

###first版本 核心功能:登录 开房 玩牌
- 登录
- agentService--------------管理与client的链接 消息队列 
- gameService---------------管理牌桌,增,删,改(玩家进,出)  配置的更新
- gameTableService----------单桌的状态管理 玩家准备,取消,开局,总结算
- gameRound-----------------单局的状态管理 开始游戏,洗牌,发牌,抓牌,操作处理..定地主.
- gameUser------------------玩家状态信息管理 个人信息 是否庄家 单局中的牌组信息
- Pokes---------------------维护单局中单个玩家的牌组信息 (手牌 弃牌 拆牌 接牌 检测出牌 推荐出牌  可操作状态 番数计算等等...)
--test
