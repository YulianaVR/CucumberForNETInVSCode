# CucumberForNETInVSCode
   Setting up Cucumber for .NET using Visual Studio Code

Setting up Cucumber for .NET using Visual Studio Code
=====================================================

Installation
------------

1.  Download and install Visual Studio Code ([Linux](https://code.visualstudio.com/docs/setup/linux) , [macOS](https://code.visualstudio.com/docs/setup/mac) and [Windows](https://code.visualstudio.com/docs/setup/windos)).
2.  Download and install .NET SDK 6.0 ([Linux, Windows, macOS](https://dotnet.microsoft.com/download/dotnet/6.0)).
3.  Install following extensions in VS Code:  
    \- C# for Visual Studio Code.  
    \- .NET Core Test Explorer.  
    \- .NET Core Tools.  
    \- C# Extensions.  
    \- Cucumber (Gherkin) Full Support.  
    \- Nuget Gallery.  
    \- SpecFlow Steps Definition Generator.  
    \- SpecFlow Tools.  
      
    ![](Images/CucumberForNETVSCodeExtensions.png)
4.  Download and install SpecFlow Template by VSCode from NuGet.org:  
      
    dotnet new --install SpecFlow.Templates.DotNet  
      
    ![](Images/SpecFlowTemplateForVSCode.png)
    
    
Create a Sample Project
-----------------------

1.  Create a sample VSCode project using the "specflowproject" template and .NET 6.0.:
    
    mkdir Sample
    cd Sample
    dotnet new specflowproject --framework net6.0
    
    ![](Images/SpecFlowTemplateForVSCode.png)
    
 2. Open sample project:
 
    code .
    
    ![](Images/SpecFlowTemplateForVSCode.png)
    
    ![](Images/SpecFlowTemplateForVSCode.png)
