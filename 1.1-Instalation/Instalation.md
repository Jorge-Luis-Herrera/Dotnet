# Dotnet

**Adding the repository in Ubuntu ,if you have other Operating system view [the oficial repository of .NET](https://dotnet.microsoft.com/en-us/download)**

    sudo add-apt-repository ppa:dotnet/backports

### Installing the SDK

    sudo apt-get update && \ sudo apt-get install -y dotnet-sdk-9.0

**To learn how to use the .NET CLI, see [.NET CLI overview.](https://learn.microsoft.com/en-us/dotnet/core/tools)**

### Installing the runtime

    sudo apt-get update && \
    sudo apt-get install -y aspnetcore-runtime-9.0


**As an alternative to the ASP.NET Core Runtime, you can install the .NET Runtime, which doesn't include ASP.NET Core support: replace aspnetcore-runtime-9.0 in the previous command with dotnet-runtime-9.0:**

    sudo apt-get install -y dotnet-runtime-9.0

### **To test the program create a Dotnet basic program**

    > dotnet new console
### **Then run the script created**

    > dotnet run

**In this folder you can see the basic program to execute and the basic basic sintax :**

    using System;

    public class Program{

        static void Main(){

            Console.WriteLine("Hi");
        }
    }

**You will see something likee this in the output if the program run correctly :**

    Hi