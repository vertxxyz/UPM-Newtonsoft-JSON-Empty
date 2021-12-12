# UPM-Newtonsoft-JSON-Empty
An empty implementation of https://docs.unity3d.com/Packages/com.unity.nuget.newtonsoft-json@latest/index.html

## Purpose
When using other JSON.Net implementations the com.unity.nuget.newtonsoft package can cause conflics.
Other implementations often use the same DLL, so this package can be manually included in a project to satisfy any dependency a package has, whilst not causing conflicts as the DLL is not provided here.