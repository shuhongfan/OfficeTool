## 安装教程

点击命令行按钮或 (Ctrl + Shift + P) 打开命令框，按需复制下面的命令，粘贴后回车以执行操作。
![命令按钮](C:\Users\shf\Downloads\OfficeTool\img\img_otp_code.gif)

使用下述命令就可以自动安装部署，如果你有别的需求，那就手动安装吧，也不难！

**安装 Microsoft 365 应用企业版 (Word, PowerPoint, Excel)**

```text
deploy /addProduct O365ProPlusRetail_zh-cn_Access,Bing,Groove,Lync,OneDrive,OneNote,Outlook,Publisher,Teams /channel Current /downloadFirst
```

**安装 Microsoft 365 应用企业版 (Word, PowerPoint, Excel) + Visio 2016**

```text
deploy /addProduct O365ProPlusRetail_zh-cn_Access,Bing,Groove,Lync,OneDrive,OneNote,Outlook,Publisher,Teams /addProduct VisioP
```

## 激活教程

点击命令行按钮或 (Ctrl + Shift + P) 打开命令框，按需复制下面的命令，粘贴后回车以执行操作。
![命令按钮](C:\Users\shf\Downloads\OfficeTool\img\img_otp_code-16582811738473.gif)

下述代命令，sethst:"xxx.xxx.xxx" 可以换成别的 KMS 主机地址。


**Microsoft 365 激活代码**

```text
ospp /insLicID MondoVolume /sethst:kms.coolhub.top /setprt:1688 /act
```

------

**Office/Visio/Project 2021 激活代码**

```text
Office 2021 激活代码
ospp /insLicID ProPlus2021Volume /sethst:kms.coolhub.top /setprt:1688 /act
//Visio 2021 激活代码
ospp /insLicID VisioPro2021Volume /sethst:kms.coolhub.top /setprt:1688 /act
//Project 2021 激活代码
ospp /insLicID ProjectPro2021Volume /sethst:kms.coolhub.top /setprt:1688 /act
```

------

**Office/Visio/Project 2019 激活代码**

```text
Office 2019 激活代码
ospp /insLicID ProPlus2019Volume /sethst:kms.coolhub.top /setprt:1688 /act
//Visio 2019 激活代码
ospp /insLicID VisioPro2019Volume /sethst:kms.coolhub.top /setprt:1688 /act
//Project 2019 激活代码
ospp /insLicID ProjectPro2019Volume /sethst:kms.coolhub.top /setprt:1688 /act
```

------

**Office/Visio/Project 2016 激活代码（Win7用户推荐）**

```text
Office 2016 激活代码
ospp /insLicID ProPlusVolume /sethst:kms.coolhub.top /setprt:1688 /act
//Visio 2016 激活代码
ospp /insLicID VisioProVolume /sethst:kms.coolhub.top /setprt:1688 /act
//Project 2016 激活代码
ospp /insLicID ProjectProVolume /sethst:kms.coolhub.top /setprt:1688 /act
```