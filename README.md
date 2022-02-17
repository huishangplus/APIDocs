# 惠商+API接入文档

## 文档说明
本文为接入联动惠商+交易的接口标准。
读者对象为联动惠商+的产品设计、开发和测试人员以及第三方接入平台或商户。

## 修改记录
|号码|修改日期|修改内容|版本号|作者|批准者|
|---|---|---|---|---|---|
|1|20180329|新建|V1.9.4|陈伟博||
|2|20180702|增加基础能力接口定义|V2.0|白辰曦||
|3|20180703|增加订单POS订单查询接口|V2.1|张桓齐||
|4|20180712|结果通知接口增加小额双免、银行卡片类型字段|V2.2|姜涛||
|5|20180716|订单同步接口响应新增3个字段（明细详见加粗字段）|V2.3|姜涛||
|6|20180925|支付、退款类接口支持第三方上送通知地址|V2.4|姜涛||
|7|20181227|新增退款查询接口|V2.5|游欢||
|7|20190508|同步接口加了优惠信息等字段|V2.6|陈伟博||
|8|20190628|支付接口新增操作员门店均为惠商体系注释|V2.7|陈伟博||
|9|20191227|支付结果通知接口添加可能会出现重复通知的注意事项|V2.8|田晓阳||
|10|20210805|被扫接口添加用户在商户appid下的唯一标识、买家支付宝账号（脱敏）等字段|V2.9|田晓阳||
|11|20220214|主扫、被扫接口添加259号文请求相关字段，同步、通知接口添加259号文响应相关字段|V3.0|田晓阳||
