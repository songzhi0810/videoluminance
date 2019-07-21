1.どんな処理を実装したのか
--------------
はじめに、PCのカメラで動画を撮影するコードを書いた。
撮影の終了は[q]を押したタイミングとした。  
そして、撮影された動画を"output.mov"として保存した。
次に、撮影された動画から、1フレームごとに画像を出力させた。  
最後に、それぞれの画像から輝度値の平均を計算し、縦軸が輝度値、横軸が時間のグラフをプロットした。  
 
2.依存ライブラリとバージョン
-------------
openCV(4.1.0),numpy(1.16.2),matplotlib(3.0.3)
  
3.参考にしたサイトのリンク
-------------
 「OS X に OpenCV を Homebrew で入れて python で動画入出力をする」  
 https://qiita.com/daxanya1/items/4709ad8454760e17148c
 
 と、「動画を扱う　ー　OpenCV-Python Tutorials 1 documentation」
 http://labs.eecs.tottori-u.ac.jp/sd/Member/oyamada/OpenCV/html/py_tutorials/py_gui/py_video_display/py_video_display.html
 
 の、「カメラの映像を動画を保存する」のコードを参考にした。  
 
 「Python, OpenCVを用いて動画を画像へ変換する（動画から画像の切り出し）-あさの畑」  
 https://www.asanohatake.com/entry/2018/11/20/073000  
 の、「動画から画像への変換（フレームごと）」のコードを参考にした。  

4.実行の様子のスクリーンショット
-------------
1.動画を撮影  
![1-1](/1-1.png)
2.1フレームごとに画像を出力
![1-2](/1-2.png)
3.輝度値のグラフをプロット
![1-3](/1-3.png)
