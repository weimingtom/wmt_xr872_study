# wmt_xr872_study
My XR872 and XR808 study  

## msys dev env  
search baidupan, msys_xr872_v1.rar  

## 使用体会  
我试了一下烧录运行xr872的wlan_demo例子，效果如图，几个体会  
（1）烧录可以不按按钮，自动完成，但可能需要按一下reset按钮重启单片机  
（2）烧录速度可能会较慢，有时候波特率会很低（烧录程序会自动更改），可以停止再重新烧录，  
直到波特率稳定在较高的数值，以加快烧录速度。  
（3）wlan_demo是一个串口控制台，需要完整的命令才会执行，例如输入echo是执行失败的，  
需要输入echo hello才会执行成功，详细需要看机芯智能的文档《快速入门V1.1.pdf》（Wifi语音模组->开发板），  
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

## xr808, 安信可, 博安通新品, NodeMCU系列wifi开发板冷启动低功耗XW-01-Kit CH340  
https://docs.ai-thinker.com/xr  
https://github.com/Ai-Thinker-Open/Ai-Thinker-Open_XR808_SDK  
https://aithinker.blog.csdn.net/article/details/108975656  

## （TODO，待补充）xr806, xr808  
* xr806 sdk (rtos version, hos version), TODO: 补充这两种SDK的区别和baidupan文件名位置  
* xr806 rtos sdk和r128在API命名方面上有区别, 不能通用  
