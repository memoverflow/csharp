#C#开始

我们接下来的很多代码都是以vs2012为开发工具构建的，当然，第一个应用程序毋庸置疑的就是"hello world"。

```
using System;
namespace Wrox
{
    public class MyFirstClass
    {
        static void Main()
        {
            Console.WriteLine("hello world.");
            Console.ReadLine();
            return;
        }
    }
}
```
将上面的文件通过vs或者记事本打开，保存成以.cs结尾的文件，我们可以用C#的命令行工具csc.exe编译源代码，例如：

```csc First.cs```

如果你想通过命令行的方式编译源代码，你必须使用.NET命令行工具，这个命令行工具只有你安装了完整的.NET环境才有。
将命令行保存成可执行文件First.exe，如下面的格式，双击运行：
```
csc First.cs
Microsoft (R) Visual C# Compiler version 12.0.21005.1
for C# 5.0
Copyright (C) Microsoft Corporation. All rights reserved.
First.exe
Hello from Wrox.
```

