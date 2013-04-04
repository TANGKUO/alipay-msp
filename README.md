## Alipay MSP ##

**[支付宝快捷支付(无线)](https://b.alipay.com/order/productDetail.htm?productId=2012120700377310)** 是一种程序式的支付方式，在手机、掌上电脑等无线设备的应用程序内，买家可通过支付宝进行付款购买特定服务或商品，资金即时到账。

支付宝提供SDK（alipay_msp.jar），但是如果你的项目采用Maven管理依赖，使用此SDK便不方便。此项目仅仅是将alipay_msp.jar重新打包并发布到Maven中央库，以便Maven管理的Android项目使用。


### 如何使用 ###
在pom.xml中添加如下依赖：
```xml
  <dependency>
		<groupId>com.belerweb</groupId>
		<artifactId>alipay-msp</artifactId>
		<version>20121026</version>
	</dependency>
```

