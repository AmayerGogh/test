Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes.

我要进行一次错误的提交

特约配置
<appSettings>
    <!--是否显示窗体,默认0不显示-->
    <add key="IsShowForm" value="1" />

    <add key="UserName" value="WFQX-00001"/>
    <add key="Password" value="1q2w3e4r5t"/>
    <!--城市编码-->
    <add key="CityCode" value="0" />
    <!--交强险续保期天数-->
    <add key="ForceRenewalDay" value="90" />
    <!--商业险续保期天数-->
    <add key="BizRenewalDay" value="90" />
    <!--地址-->
    <add key="Address" value="北京市海淀区" />
    <!--邮编-->
    <add key="PostCode" value="100010" />
    <!--打印发票类型 0普通增值税发票 2增值税电子普通发票-->
    <add key="InvoicePrintType" value="0" />
    <!--决策方案选择方式（1：渠道系数最低；2：渠道系数最高；3：自定义-->
    <add key="schemeType" value="1" />
    <!--自主核保系数-->
    <add key="SelfUnderWritingRate" value="" />
    <!--渠道系数-->
    <add key="ChannelRate" value="" />
    <!--手续费-->
    <add key="CommissionBrokerFee" value="" />
    <add key="TaxOfficeName" value="" />
    <add key="MessageCenterUrl" value="http://111.198.29.209:8012/messagecenter.asmx" />

    <!--初始化窗口数量-->
    <add key="FormCount" value="5" />
  </appSettings>
1 解决客户问题
2 续保分支测试,续保合并到主干后的测试
3 处理由于续保加* 所带来的问题,重点在503超时

1 测试重构后的流程 
2 时刻盯着已经部署重构后的代码的渠道
3 处理已存在的问题
  (1)壁虎:有一个未处理弹框  错误比占到15% 本地不容易复现,
  (2)503超时 错误比已从15降低到5% 仍继续关注
  (3)类似 "ApplyAfterCheckDivDialog_timer_ExcuteCompleted" 的流程超时问题
4 特约检索未合并



已部署 errorcode first
48:4D:7E:AC:69:4C-PA-ShenZhen-SenNaMei


上海名阳                    00:16:3E:10:6C:05-PA-ShangHai-MingYang
佛山通宝                    48:4D:7E:A8:71:20-PA-FoShan-TongBao  商业险转保验证码
武汉                        00:0A:EB:99:85:08-PA-WuHan-BaDaTong-XB（没更新重复投保）
永宏                      60:45:CB:6C:2A:69-PA-FZ-GDDZ      565 065 343

台湾诚隆集团-平安车险-苏州  4C:CC:6A:D6:B1:C4-PA-SuZhou-ChengLongJiTuan 848 893 592（过车，未处理弹框户）


北方华鹏                    44:37:E6:9B:B8:76-PA-BJ-BeiFangHuaPeng  192.168.1.151

长春华阳 245608195
杭州华策
运通国瑞  878 129 848 
运通冀迪  328931167
广州瀚福福特  660774012 668813
润宏迪 rhd.7766.org:81
运通嘉奥 


米米养车138(庞大华业)    158
万车达 todo
润华 228664963   jp861y
润宏迪  258293461 
北京兴飞驰   735164047    
建发保时捷  




座位数与报价串一致但与交管平台查询的不一致，不再报价，报价串座位数为：5，交管平台座位数为：5
http://125.208.9.186:8022/quote/successdetial?agentId=4066&city=%E5%8C%97%E4%BA%AC&source=%E5%B9%B3%E5%AE%89&isSuccess=false&date=2018-07-05%2000:00:00%20%E8%87%B3%202018-07-05%2023:59:59&selectTime=0&errcode=-88815

http://a.airen66.cn/?m=vod-play-id-51480-src-1-num-1.html