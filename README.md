Prank only works in IE

```
Set objExplorer = CreateObject("InternetExplorer.Application")
With objExplorer
        .Navigate strPath
        .ToolBar = 1
        .StatusBar = 1
        .Width = 1000
        .Height = 593 
        .Left = 1
        .Top = 1
        .Visible = 1
        .Navigate("https://www.google.com")
End With
```
