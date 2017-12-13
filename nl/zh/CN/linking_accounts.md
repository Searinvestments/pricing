---



copyright:

  years: 2015, 2017
lastupdated: "2017-11-09"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# 链接 Bluemix 和 SoftLayer 帐户
{: #unifyingaccounts}

您可以链接 {{site.data.keyword.Bluemix_notm}} 和 SoftLayer 帐户以利用组合资源。链接 {{site.data.keyword.Bluemix_notm}} 和 Softlayer 帐户后，您将收到单个 {{site.data.keyword.Bluemix_notm}} 发票。如果您有现有的 {{site.data.keyword.Bluemix_notm}} 帐户，那么通过 {{site.data.keyword.Bluemix_notm}} 对 SoftLayer 资源进行记帐会在链接帐户之后启动的新记帐周期生效。


**重要信息：**{{site.data.keyword.Bluemix_notm}} 中的所有链接帐户都必须是现买现付帐户。您可以创建新的现买现付帐户，链接现有的现买现付帐户，或者链接现有试用帐户（此帐户随后将升级为现买现付帐户）。但不能链接 {{site.data.keyword.Bluemix_notm}} 预订帐户。

您必须是 SoftLayer 帐户中的主用户，才能链接帐户。

链接帐户时：

* 必须使用 IBM 标识凭证来访问 SoftLayer 和 {{site.data.keyword.Bluemix_notm}} 帐户。
* 将对全体 {{site.data.keyword.Bluemix_notm}} 费用应用所有现有的 SoftLayer 折扣。
* 您将收到一张以美元 (USD) 计费的发票。
* 您可以在 {{site.data.keyword.BluSoftlayer}} 控制台中监视 {{site.data.keyword.Bluemix_notm}} 资源的使用情况。

**注意：**帐户链接之后即无法对其取消链接。  

作为主用户，请完成以下步骤来链接您的 {{site.data.keyword.Bluemix_notm}} 和 SoftLayer 帐户：

 1. 在客户门户网站中，单击**链接 {{site.data.keyword.Bluemix_notm}} 帐户**。
 2. 阅读并接受链接 SoftLayer 和 {{site.data.keyword.Bluemix_notm}} 帐户的条款。
 3. 要求时，提供与 {{site.data.keyword.Bluemix_notm}} 帐户相关联的电子邮件地址。如果您没有 {{site.data.keyword.Bluemix_notm}} 帐户，请提供要使用的电子邮件地址，然后遵循指示受邀加入 {{site.data.keyword.Bluemix_notm}} 并创建帐户。

链接帐户后，SoftLayer 控制台菜单栏中将提供**转至 {{site.data.keyword.Bluemix_notm}}**。单击此链接可带您进入 {{site.data.keyword.Bluemix_notm}} 登录页面。

## 链接帐户时 {{site.data.keyword.Bluemix_notm}} 使用情况的帐单
{: #bill_usage}

在您链接 {{site.data.keyword.Bluemix_notm}} 和 SoftLayer 缴费帐户之后，下一个记帐周期将会记入单个 {{site.data.keyword.Bluemix_notm}} 帐单。
{:shortdesc}

{{site.data.keyword.Bluemix_notm}} 使用情况周期以日历月为基础，因此您的帐户会在每月的建立收费协议的记帐日进行记帐。使用 SoftLayer，您的使用情况周期从您开始使用 SoftLayer 开始，因此每月会在您注册 SoftLayer 帐户的那一天进行记帐。 

链接帐户时，{{site.data.keyword.Bluemix_notm}} 使用量将继续度量并计入当前月份周期内，并会在 {{site.data.keyword.Bluemix_notm}} 发票上对该使用量进行记帐。从下个月的第一天开始，您的 {{site.data.keyword.Bluemix_notm}} 和 SoftLayer 费用将会一并列在 {{site.data.keyword.Bluemix_notm}} 发票上。

例如，如果您在 2017 年 4 月 16 日链接了帐户，那么您将获得 4 月使用量的 {{site.data.keyword.Bluemix_notm}} 发票。根据链接帐户的时间，您可能会收到针对 SoftLayer 使用量的单独帐单。您在五月对 SoftLayer 和 {{site.data.keyword.Bluemix_notm}} 的使用量将通过 {{site.data.keyword.Bluemix_notm}} 帐户记帐。

![链接 Bluemix 和 SoftLayer 帐户摘要](BluemixSoftLayerBill.svg)

链接帐单后，{{site.data.keyword.Bluemix_notm}} 发票将列出针对所使用的每个资源的不同费用。

## 基于 API 的 Bluemix 服务
{: #api_based_bluemix_services}

以下列表包含可以设置为与应用程序代码一起运行的服务：
{:shortdesc}

并非这些服务的所有套餐都可与链接的 {{site.data.keyword.Bluemix_notm}} 和 SoftLayer 帐户一起使用。只有针对“现买现付”帐户启用的套餐可用于与相链接的帐户一起使用。但是，如果您具有单独记帐的独立 {{site.data.keyword.Bluemix_notm}} 帐户，那么您可以对这些服务中的任何一个使用任何套餐。

* {{site.data.keyword.alchemyapishort}}
* {{site.data.keyword.alertnotificationshort}}
* {{site.data.keyword.sparks}}
* {{site.data.keyword.appseccloudshort}}
* {{site.data.keyword.blockchain}}
* {{site.data.keyword.cloudant}}
* {{site.data.keyword.conceptinsightsshort}}
* {{site.data.keyword.iotmapinsights_short}}
* {{site.data.keyword.dashdbshort}}
* {{site.data.keyword.dialogshort}}
* {{site.data.keyword.documentconversionshort}}
* {{site.data.keyword.twittershort}}
* {{site.data.keyword.weather_short}}
* {{site.data.keyword.iotdriverinsights_short}}
* {{site.data.keyword.geospatialshort_Geospatial}}
* {{site.data.keyword.graphshort}}
* {{site.data.keyword.iotelectronics}}
* {{site.data.keyword.languagetranslationshort}}
* {{site.data.keyword.messagehub}}
* {{site.data.keyword.mqa}}
* {{site.data.keyword.mobileappbuilder_short}}
* {{site.data.keyword.mql}}
* {{site.data.keyword.nlclassifiershort}}
* {{site.data.keyword.objectstorageshort}}
* {{site.data.keyword.personalityinsightsshort}}
* {{site.data.keyword.presenceinsightsshort}}
* {{site.data.keyword.relationshipextractionshort}}
* {{site.data.keyword.retrieveandrankshort}}
* {{site.data.keyword.servicediscoveryshort}}
* {{site.data.keyword.speechtotextshort}}
* {{site.data.keyword.sqldb}}
* {{site.data.keyword.streaminganalyticsshort}}
* {{site.data.keyword.texttospeechshort}}
* {{site.data.keyword.toneanalyzershort}}
* {{site.data.keyword.tradeoffanalyticsshort}}
* {{site.data.keyword.visualinsightsshort}}
* {{site.data.keyword.visualrecognitionshort}}
* {{site.data.keyword.workflow}}
* {{site.data.keyword.workloadscheduler}}
