# 第1次練習-練習-PC1
>
>學號：109111139 
><br />
>姓名：繆昊廷 
><br />
>作業撰寫時間：30mins
><br />
>最後撰寫文件日期：2022/09/22
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x]說明內容
- [x]個人認為完成作業須具備觀念

## 說明程式與內容


下段程式碼則為使用後結果：顯示Hello App字串

```csharp
protected void Page_Load(object sender, EventArgs e)
        {
            Response.Write("Hello App");
        }
```

若要於內文中標示部分.aspx檔，則使用以下標籤` ```html 程式碼 ``` `，
下段程式碼則為使用後結果：無

```html
<%@ Page Language="C#" AutoEventWireup="true" ...>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
<meta http-equiv="Content-Type" ...>
    <title></title>
</head>
<body>
    <form id="form1" runat="server">
        <div>
        </div>
    </form>
</body>
</html>
```


## 個人認為完成作業須具備觀念

需要會用Response.Write來顯示字串，並且要在最後加上分號，如果沒有分號，會認為是語法不對，會無法執行。

