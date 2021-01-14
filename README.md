# wmt_xr872_study
My XR872 study

## msys dev env  
search baidupan, msys_xr872_v1.rar  

## 使用体会  
我试了一下烧录运行xr872的wlan_demo例子，效果如图，几个体会  
（1）烧录可以不按按钮，自动完成，但可能需要按一下reset按钮重启单片机  
（2）烧录速度可能会较慢，有时候波特率会很低（烧录程序会自动更改），可以停止再重新烧录，  
直到波特率稳定在较高的数值，以加快烧录速度。  
（3）wlan_demo是一个串口控制台，需要完整的命令才会执行，例如输入echo是执行失败的，  
需要输入echo hello才会执行成功，详细需要看机芯智能的文档（Wifi语音模组->开发板），  
如果看芯之联的文档可能会讲得不清楚：  
http://docs.aimachip.com/zh_CN/latest/file/wifi_audio.html  
https://xradiotech-developer-guide.readthedocs.io/zh/latest/zh_CN/get-started/  
简单说，开发板是机芯智能的，要看机芯智能的文档，而开发SDK看芯之联的文档  

## 机芯智能  
http://docs.aimachip.com/zh_CN/latest/file/sdk.html  
https://github.com/jixinintelligence/xradio-skylark-sdk  

## 芯之联  
https://xradiotech-developer-guide.readthedocs.io/zh/latest/zh_CN/get-started/#_1  
https://github.com/XradioTech/xradio-skylark-sdk  

## 新品发布|高性价比、低功耗，iFLYOS XR872开发套件  
https://segmentfault.com/a/1190000021864206  
MT8516  
XR872  

## iflyos, iFLYOS XR872 开发套件  
https://www.iflyos.cn/development-kits  
http://support.iflyos.cn/hc/community/topic/  
http://bbs.xfyun.cn/forum.php?mod=forumdisplay&fid=84&page=1  
