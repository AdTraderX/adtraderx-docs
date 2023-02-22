# 对接步骤

1. 提供准备接入的应用信息

   包括但不止于应用名称、包名、下载地址、广告位截图、广告位支持物料类型（jpg、jpeg、png、gif、html等）、是否支持多地址上报、是否存在预加载（影响请求成功到展示的数据对应关系）、是否支持
   deeplink、是否可在应用内调用外部浏览器等，用于平台的接入评估。

2. 获取账号，对接信息

   与平台的商务人员沟通开始合作， 确定合作后，商务人员会在SSP平台创建相关应用和广告位信息。商务人员会提供给您 APP ID,Adslot
   ID等其他相关可直接在SSP。

3. 了解AdTraderX交易平台对接文档

    + 熟悉AdTraderX交易平台 [SSP对接文档协议](request_and_response.md)
      ，了解AdTraderX基本的请求和返回参数，示例请参考 [广告请求和返回json示例](sample_of_request_and_response.md)

    + 确定对接的广告类型和每种广告对接的物料类型

4. 开发对接协议

   根据 [SSP对接文档协议](request_and_response.md) ，结合 [广告请求和返回json示例](sample_of_request_and_response.md)
   ，开始开发。开发完毕后，测试的APP ID、Adslot ID进行测试，如果广告可以正常展示，则对接成功。


5. 小流量测试

   上述步骤完成后，进入小流量测试阶段。

   > 媒体放少量流量给到AdTraderX，核对请求数、展示、点击等数据是否一致。具体小流量开启时间，请与AdTraderX的商务人员确定。

6. 正式上线对接

   沟通确认没问题后，开始正式上线。
