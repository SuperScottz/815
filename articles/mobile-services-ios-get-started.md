<properties
	pageTitle="使用 Azure 移动服务开发 iOS 应用程序入门"
	description="遵照本教程开始使用 Azure 移动服务进行 iOS 开发。"
	services="mobile-services"
	documentationCenter="ios"
	authors="krisragh"
	manager="dwrede"
	editor=""/>

<tags
	ms.service="mobile-services"
	ms.date="04/24/2015"
	wacn.date="07/25/2015"/>

#  <a name="getting-started"></a>移动服务入门

[AZURE.INCLUDE [mobile-services-selector-get-started](../includes/mobile-services-selector-get-started.md)]

本教程说明如何使用 Azure 移动服务向 iOS 应用程序添加基于云的后端服务。

在本教程中，你将要创建一个新的移动服务，以及一个在新移动服务中存储应用程序数据的简单_待办事项列表_ 应用程序。要创建的移动服务将为服务器端业务逻辑使用 JavaScript。若要以 .NET 创建包含服务器端业务逻辑的移动服务，请参阅本主题的 [.NET 后端版本]。

> [AZURE.NOTE]若要完成本教程，你需要一个 Azure 帐户。如果你没有帐户，可以注册 Azure 试用版并获取[免费的移动服务，即使在试用期结束之后仍可继续使用这些服务](/home/features/mobile-services/#price)。有关详细信息，请参阅 [Azure 试用](/pricing/1rmb-trial target="_blank")。

##  <a name="create-new-service"></a>创建新的移动服务

[AZURE.INCLUDE [mobile-services-create-new-service](../includes/mobile-services-create-new-service.md)]

##  创建新的 iOS 应用程序

你可以在管理门户中遵照一个简易的快速入门项目来创建与你的移动服务连接的新应用程序：

1.  在管理门户中单击“移动服务”，然后单击你刚刚创建的移动服务。

2. 在“快速启动”选项卡中，单击“选择平台”下的“iOS”，然后展开“创建新的 iOS 应用程序”。此时将显示步骤，描述如何创建与移动服务连接的 iOS 应用程序。

3. 单击“创建 TodoItem 表”以创建用于存储应用程序数据的表。

4. 在“下载并运行应用程序”下面单击“下载”。随即将会下载已连接到移动服务的示例_待办事项列表_ 应用程序的项目，以及移动服务 iOS SDK。将压缩的项目文件保存到本地计算机，并记下保存位置。

##  运行新的 iOS 应用程序

[AZURE.INCLUDE [mobile-services-ios-run-app](../includes/mobile-services-ios-run-app.md)]

<ol start="4"><li><p>返回到管理门户，单击“数据”选项卡，然后单击“TodoItem”表<strong></strong><strong></strong>。这样，你便可以浏览应用程序在表中插入的数据。<p></li></ol></p>

##  <a name="next-steps"></a>后续步骤
了解如何在移动服务中执行其他重要任务：

* [将移动服务添加到现有应用程序]<br/>了解有关使用移动服务存储和查询数据的详细信息。

* [脱机数据同步入门]<br/>了解如何使用脱机数据同步来使应用程序保持较高的响应能力和稳健性。

* [向现有应用程序添加身份验证]<br/>了解如何使用标识提供程序对应用程序的用户进行身份验证。

* [向现有应用程序添加推送通知]<br/>了解如何向应用程序发送一条很基本的推送通知。


<!-- Anchors. -->

[Getting started with Mobile Services]: #getting-started
[Create a new mobile service]: #create-new-service
[Define the mobile service instance]: #define-mobile-service-instance
[Next Steps]: #next-steps

<!-- Images. -->

[6]: ./media/mobile-services-ios-get-started/mobile-portal-quickstart-ios.png
[7]: ./media/mobile-services-ios-get-started/mobile-quickstart-steps-ios.png
[8]: ./media/mobile-services-ios-get-started/mobile-xcode-project.png

[10]: ./media/mobile-services-ios-get-started/mobile-quickstart-startup-ios.png
[11]: ./media/mobile-services-ios-get-started/mobile-data-tab.png
[12]: ./media/mobile-services-ios-get-started/mobile-data-browse.png


<!-- URLs. -->

[将移动服务添加到现有应用程序]: mobile-services-dotnet-backend-ios-get-started-data
[脱机数据同步入门]: mobile-services-ios-get-started-offline-data
[向现有应用程序添加身份验证]: mobile-services-dotnet-backend-ios-get-started-users
[向现有应用程序添加推送通知]: mobile-services-dotnet-backend-ios-get-started-push


[Mobile Services iOS SDK]: https://go.microsoft.com/fwLink/p/?LinkID=266533
[Management Portal]: https://manage.windowsazure.cn/
[XCode]: https://go.microsoft.com/fwLink/p/?LinkID=266532
[.NET 后端版本]: mobile-services-dotnet-backend-ios-get-started

<!---HONumber=HO63-->