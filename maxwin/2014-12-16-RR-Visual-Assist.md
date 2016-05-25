layout: post
title: RR Visual Assist
comments: true
date: 2014-12-16 11:24:57
---

Version 0.0.10.6

<!--more-->

此次最主要的更新項目為<font color="blue">新增</font>`視覺輔助功能`

## 視覺輔助功能

![Visual Assist On/Off 預設為Off](/image/Radxa/device.png)

在Off的情況下與之前的版本一模一樣。

反之在On的情況，在APP初始畫面下才會去監聽鍵盤事件，且因為要搭配ATM鍵盤的關係(ATM鍵盤的Cancel鍵對應到Android的Back)，會將Back功能取消掉。

#### 按鍵

 * 0~9
 * Enter
 * Cancel(清空輸入資料)

## 音樂與影片

語音檔：

 * v1.ogg : input time out
 * v2.ogg : 路線不存在
 * v3.ogg : 叫車失敗
 * v4.ogg : 叫車成功
 * v5.ogg : 叫車中

在語音播放特別要注意的地方是，播放時語音可能會遺漏約0.5秒左右，因此在<font color="blue">製作語音檔必須在前面加入0.5秒的空白聲音</font>

語音的播放位置先暫定放在`Music`資料夾內

影片的部分要搭配播放語音，所以得要靜音

---

v1.ogg : 未按確認鍵，請重試
v2.ogg : 未停靠本站，請重試
v5.ogg : 系統叫車中
v6.ogg : 尚未發車，請稍候重試

sxx.ogg : 叫車成功，預計xx分鐘後到達

ex:
s9.ogg : 叫車成功，預計9分鐘後到達
s30.ogg : 叫車成功，預計30分鐘後到達

dyy.ogg : Ding-dong yy號公車即將到達

ex:
d1031.ogg : Ding-dong 1031號公車即將到達
d9.ogg : Ding-dong 9號公車即將到達

