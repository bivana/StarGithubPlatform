# 用户
1. 用户可以通过Github和微信快捷登录
2. 用户必须填写关联的Github账户名称，进行关联；服务必须检测该账户完整性（完整性后续讨论）
3. 账户可以关联Github小号，小号一般用于回赞用，可以多个
4. 账户可以曝光他最优先需要点赞的项目
5. 点赞小号，必须满足基本的信息完整，有正常的活动，不能别识别为脚本号

# 功能
1. 用户A 给 用户B的项目点赞后，服务记录状态，B欠A项目一次点赞
2. B无论用哪个github账户给A点赞后，都计B为A点赞一次，2者扯平
3. 当B欠赞数大于N值后，服务需要通知B进行还赞，不然对B进行冻结处理。

# 前端
前端为小程序实现，设计规范参考微信，需具体讨论