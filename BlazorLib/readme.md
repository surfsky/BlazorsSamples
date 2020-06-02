# Blazor 测试项目


项目结构
```
    Program.cs               程序入口，会调用startup.cs
    startup.cs               配置，启用blazor中间件
    App.razor                Blazor 程序入口，里面指定了layout和路由
    _imports.razor           预置 using 代码
    /wwwroot                 客户端文件，如css、js等
    /Data                    cs代码，里面放了天气预报的服务类
    /Pages                   页面代码。razor页面顶部增加@page，才能被blazor路由处理
        _Host.cshtml         根目录页面。里面将 app.razor 作为主组件。
        Index.razor          主页面，一些欢迎文本
        Counter.razor        计数器演示。点击按钮后数字增加。
        FetchData.razor      天气数据展示演示。
    /Shared                  公用 razor 组件
        MainLayout.razor     布局组件，含左侧的菜单和右侧的主区域
        NavMenu.razor        导航组件
        SurveyPrompt.razor   调查组件
```


# 学习资料

> 官方教程： https://docs.microsoft.com/zh-cn/aspnet/core/blazor/?view=aspnetcore-3.1

# Author

surfsky.cnblogs.com
surfsky.github.com


# Targets

- [x] 跑通主项目
- [x] Blazors 组件库项目
- [x] 使用三方 blazor 组件: MatBlazor
- [x] 使用三方 blazor 组件: Radzen
- [x] 使用三方 blazor 组件: BlazorStrap
- [ ] ChatJsBlazor
- [ ] 弹出对话框
- [ ] 其它控件