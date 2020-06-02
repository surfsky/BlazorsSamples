# TestBlazors

ASPNETCORE Blazor testing.

<https://github.com/surfsky/TestBlazors>

# Projects


- TestBlazor         : Blazor server side basic demo
- TestBlazorAuth     : Blazor server side & auth
- TestBlazorAssembly : Blazor assembly & auth
- TestBlazorPWA.*    : Blazor PWA(server, client, shared)
- TestBlazorLib      : Blazor lib project and 3-party ui lib


# 适合场合分析

Razor Pages 
    
    作为mvc方案的替代
    它将 viewmodel 和 controller 进行了合并，更容易维护
    适合公网 Web 站点

Blazor WebAssembly 

    初始传输有 18.8 M, 刷新后需要 35.8 K
    不适合公网服务，首次体验过差。
    可开发离线应用、企业内部应用
    可作为离线app框架，未来可开发为 ios、andoid 应用，考虑作为跨平台App方案。
    如果有加载进度展示会更好些，缓解等待焦虑。

Blazor server

    需要客户端和服务器端保持连接（用signalr）
    需要在服务器端为每个客户端保持页面状态，占内容
    适合内部局域网的运用
    作为公网应用执保留态度，可以支撑多少用户待测试

Blazor WebAssembly 

    适合各类内部应用（比如公司内部管理系统）。


# Ref

<https://www.cnblogs.com/yilezhu/p/11031441.html>
