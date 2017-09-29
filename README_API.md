# JrezAPI（直连api） #
`测试环境地址`： http://jrezapitest.bestwehotel.com
`生产环境地址`： http://jrezapi.bestwehotel.com
----------

## 预订下单接口 ##
`接口地址`:  /resv/booking

`请求类型`：POST
`请求Headers`：  "Content-Type":"application/json";"authorization":"7497d5a9fbcf9399f9ae0c5bd304e309"
`请求参数`： 

| 层级 | 参数名 |类型| 描述 |
| :------------| :------------|:---------: |:---------------:|
| 0 | whHotelId | String | wehotel酒店ID（必传） |
| 0 | whCrsnum | String | WeHotel CRS订单号（必传） |
| 0 | channelResvNum | String | 渠道订单号（必传） |
| 0 | iataCode |  String | IATA号（必传） |
| 0 | holdResv | String | 1:Hold单标识,待解HOLD|
| 0 | isAssure | String | 担保类型 0:现付;1:担保单;2:预付单 ;3:公司担保;4:全额支付担保;5:信用卡担保;6:首晚担保;7:信用住 （必传）|
| 0 | sourceType | String | 来源类型 |
| 0 | sourceId | String | 来源ID|
| 0 | resvTotalRevenue | Double | 预订总金额（必传）|
| 0 | resvCurrency | String | 订单货币单位 |
| 0 | remark | String | 订单备注|
| 0 | stayDetailDomain | StayDetailDomain | 预订基本信息（必传） |
| 1 | inDate | Date | 入住日期 格式:yyyy-MM-dd（必传）|
| 1 | nights | Integer | 入住天数 （必传）|
| 1 | roomCode | String | 房型代码（必传）|
| 1 | rateCode | String | 价格代码 （必传）|
| 1 | rooms | Integer | 入住房间数 （必传）|
| 1 | adults | Integer | 成人数 （必传）|
| 1 | children | Integer | 小孩数  （必传）|
| 1 | arrivalLastTime | Time | 客人最晚到店时间 格式为HH:mm|
| 1 | arrivalEarlyTime | Time | 客人最早到店时间格式为HH:mm|
| 0 | resvGuestDomain | ResvGuestDomain | 客人信息（必传）|
| 1 | guestName | String | 客人姓名（必传）|
| 1 | guestMobile | String | 移动电话 （必传）|
| 1 | otherGuests | List&lt;String&gt; | 其他客人姓名|
| 0 | resvContactDomain | ResvContactDomain | 联系人信息 |
| 1 | contactName | String | 联系人姓名|
| 1 | contactPhone | String | 联系人电话|
| 1 | contactMobile | String | 联系人手机|
| 1 | contactEmail | String | 联系人Email|
| 0 | resvRates | List&lt;ResvRateDomain&gt; | 每日价列表 （必传）|
| 1 | stayDate | Date | 日期 yyyy-MM-dd （必传）|
| 1 | rate | Double | 房费 （必传）|
| 1 | extraCharge | Double | 加床费|
| 1 | currency | String | 货币单位 CNY:人民币|
| 1 | breakfastNum | Integer | 免费早餐数量|
| 0 | resvMemberDomain | ResvMemberDomain | 会员信息 |
| 1 | memberId | String | 会员ID（必传） |
| 1 | memberCard    | String | 会员卡号（必传） |   
| 1 | memberName | String | 会员名称（必传） |
| 1 | memberGrade | String | 会员等级（必传） |
| 1 | memberTel | String | 会员电话（必传） |
| 0 | resvCoupons | List&lt;ResvCouponDomain&gt; | 优惠券信息 |
| 1 | couponCount | Integer | 优惠券总数量 （必传）|
| 1 | couponTotalAmount | Double | 优惠券总金额 （必传）|
| 1 | couponDetails | List&lt;CouponDetailDomain&gt; | 券的详细信息 （必传）|
| 2 | couponType | String | 券类型 O:抵用券;R:房券；F:免房券；V:增值券（必传）|
| 2 | couponNo | String | 券号（必传）|
| 2 | couponAmount | Double | 券的金额（必传）|
| 2 | couponSubtype | String | 优惠券子类 B:早餐券；W:洗衣券；U:房型免费升级券；L:大堂酒吧券|
| 1 | couponBears | List&lt;CouponBearDomain&gt; | 优惠券成本承担信息 （必传）|
| 2 | bearer | String | 承担方 1、平台（Wehotel） 2、门店 3、品牌 4、渠道 （必传）|
| 2 | percent | Double | 承担百分比 例如：100代表100%,80代表80%（必传）|
| 2 | amount | Double | 承担金额（必传）|

----------
`请求参数示例`：
```json
```

----------
`返回参数`：

|层级| 参数名 |类型| 描述 |
|:------------:| :------------:|:---------:|:---------------:|
|0| resultCode | String | 返回结果状态码 |
|0| resultDesc | String | 返回结果描述 |
|0| whCrsnum | String | wehotel CRS订单号 |
|0| confirmNum | String | 订单确认号 |
|0| status | Integer | 订单状态 0:待酒店确认 |

`返回参数示例`：

```json
```

----------
## 预订取消接口 ##
`接口地址`:  /resv/cancel

`请求类型`：POST
`请求Headers`：  "Content-Type":"application/json";"authorization":"7497d5a9fbcf9399f9ae0c5bd304e309"
`请求参数`： 

| 层级 | 参数名 |类型| 描述 |
| :------------| :------------|:---------: |:---------------:|
| 0 | whHotelId | String | wehotel酒店ID（必传） |
| 0 | whCrsnum | String | WeHotel CRS订单号（必传） |
| 0 | channelResvNum | String | 渠道订单号 |
| 0 | resvPaymentDomain | ResvPaymentDomain | 订单支付信息 |
| 1 | paymentType | String | 支付类型 1:全额预付2:首晚预付 |
| 1 | paymentStatus | String | 支付状态 0:未支付 1:已支付  5:已退款 |
| 1 | paymentAmount | Double | 支付/退款金额 |
| 1 | paymentCurrency | String | 支付货币类型 |
| 1 | paymentSource | String | 支付来源 1:快钱  2:支付宝 3:银联  4:微信 |
| 1 | paymentSubSource | String | 交易子来源 |
| 1 | paymentTaxes | Double | 已支付的税金 |
| 1 | tradeNo | String | 交易编号 |
| 1 | accountType | String | 帐户类型1：Wehotel帐户（平台） 2：门店帐户  3：品牌/集团帐户  4：第三方渠道自身帐户 |

----------
`请求参数示例`：
```json
```

----------
`返回参数`：

|层级| 参数名 |类型| 描述 |
|:------------:| :------------:|:---------:|:---------------:|
|0| resultCode | String | 返回结果状态码 |
|0| resultDesc | String | 返回结果描述 |
|0| whCrsnum | String | wehotel CRS订单号 |
|0| cxlConfirmNum | String | 取消确认号 |

`返回参数示例`：

```json
```

----------
## 预订支付接口 ##
`接口地址`:  /resv/pay

`请求类型`：POST
`请求Headers`：  "Content-Type":"application/json";"authorization":"7497d5a9fbcf9399f9ae0c5bd304e309"
`请求参数`： 

| 层级 | 参数名 |类型| 描述 |
| :------------| :------------|:---------: |:---------------:|
| 0 | whHotelId | String | wehotel酒店ID（必传） |
| 0 | whCrsnum | String | WeHotel CRS订单号（必传） |
| 0 | channelResvNum | String | 渠道订单号 |
| 0 | paymentType | String | 支付类型 1:全额预付2:首晚预付 （必传）|
| 0 | paymentStatus | String | 支付状态 0:未支付 1:已支付  5:已退款（必传） |
| 0 | paymentAmount | Double | 支付/退款金额（必传） |
| 0 | paymentCurrency | String | 支付货币类型 |
| 0 | paymentSource | String | 支付来源 1:快钱  2:支付宝 3:银联  4:微信 （必传）|
| 0 | paymentSubSource | String | 交易子来源 |
| 0 | paymentTaxes | Double | 已支付的税金 |
| 0 | tradeNo | String | 交易编号 |
| 0 | accountType | String | 帐户类型1：Wehotel帐户（平台） 2：门店帐户  3：品牌/集团帐户  4：第三方渠道自身帐户 |

----------
`请求参数示例`：
```json
```

----------
`返回参数`：

|层级| 参数名 |类型| 描述 |
|:------------:| :------------:|:---------:|:---------------:|
|0| resultCode | String | 返回结果状态码 |
|0| resultDesc | String | 返回结果描述 |

`返回参数示例`：

```json
```

----------

`备注`：
*error code说明：*
    "200": "成功"
    "400": "业务错误"，会有对应的resultDesc说明
    "500": "系统错误"

