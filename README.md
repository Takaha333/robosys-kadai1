# ロボットシステム学課題1  
LEDを制御するデバイスドライバの制作  
## 概要  
メモリアドレスへ0,1を書き込むことでGPIOピンを操作する  
## 使用した物  
・Raspberry PI3 Model B+  
・LED  
・抵抗200Ω  
## 操作方法  
以下のコマンドで操作  
0を入力で消灯　1を入力で点灯  
echo 0 > /dev/mymyled0  
echo 1 > /dev/mymyled0  
  
実演動画　https://www.youtube.com/watch?v=o73ncHTNuG0
