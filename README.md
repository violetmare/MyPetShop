Warning；MyPetShop.Web 是老式的 ASP.NET 网站项目（Web Site Project，不是 Web应用程序项目），需要用 aspnet_compiler.exe 编译，而这个编译器只能在传统 .NET Framework 版 MSBuild 下跑。

Why the project which is have this problem： MyPetShop 是微软很老的示例项目（ASP.NET 2.0/3.5 时代），本身就是给老版本 Visual Studio + .NET Framework 用的。如果你用命令行 dotnet build，或者当前电脑只装了较新的 .NET SDK 而没装 .NET Framework 相关组件，就会触发这个问题。 
这个只是让本人熟悉GITHUB发布和练习
