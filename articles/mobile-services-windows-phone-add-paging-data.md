<properties pageTitle="将分页添加到数据 （Windows Phone） |移动开发人员中心" metaKeywords="" description="了解如何使用分页来管理移动服务返回给 Windows Phone 应用程序的数据量。" metaCanonical="" services="" documentationCenter="Mobile" title="使用分页优化移动服务查询" authors="glenga" solutions="" manager="" editor="" />
<tags ms.service=""
    ms.date="10/11/2014"
    wacn.date="04/11/2015"
    />

# 使用分页优化移动服务查询

[WACOM.INCLUDE [mobile-services-selector-add-paging-data](../includes/mobile-services-selector-add-paging-data.md)]

本主题说明如何使用分页来管理从 Azure 移动服务返回给 Windows Phone 应用程序的数据量。在本教程中，将在客户端上使用 **Take** 和 **Skip** 查询方法来请求特定的数据"页"。

>[WACOM.NOTE]为了防止移动设备客户端上发生数据溢出，移动服务实施了自动页限制，该限制默认为每个响应中最多 50 个项。通过指定页大小，你最多可以在响应中显式请求 1,000 个项。

本教程以前面的教程[将移动服务添加到现有应用程序](/zh-cn/documentation/articles/mobile-services-windows-phone-get-started-data)中的步骤和示例应用程序为基础。在开始本教程之前，必须先完成以上所提教程。  

[WACOM.INCLUDE [mobile-services-windows-dotnet-paging](../includes/mobile-services-windows-dotnet-paging.md)]

## <a name="next-steps"> </a>后续步骤

演示移动服务中数据处理基础知识的系列教程到此结束。建议进一步了解以下移动服务主题：

* [身份验证入门]
  <br/>了解如何使用 Windows 帐户对应用程序的用户进行身份验证。

* [推送通知入门] 
  <br/>了解如何将非常简单的推送通知发送到您的应用程序。

<!-- Anchors. -->

[后续步骤]:#next-steps

<!-- Images. -->


<!-- URLs. -->
[移动服务入门]: /zh-cn/documentation/articles/mobile-services-windows-phone-get-started/
[数据处理入门]: /zh-cn/documentation/articles/mobile-services-windows-phone-get-started-data/
[身份验证入门]: /zh-cn/documentation/articles/mobile-services-windows-phone-get-started-users/
[推送通知入门]: /zh-cn/documentation/articles/mobile-services-windows-phone-get-started-push/


[管理门户]: https://manage.windowsazure.cn/
