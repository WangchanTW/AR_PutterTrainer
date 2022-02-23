# AR_PutterTrainer
The main idea is built on OpenCV with the concept of camshift and kalman filter
This AR related project was developed when 2015 as exchange student in University of Tsukuba . However, unfortunately, the "homography.xml" has been lost, so it is hard to run this project unless you update a new homography metrix. If you are interested in how to create the matrix, you can contact me

此為在2015筑波大學交換時的學期成果
主要使用C/C++撰寫，使用OpenCV結合Camshift以及Kalman filter達到動態追蹤的效果
並且利用影像投影技術，實現虛擬實境(AR)的高爾夫推桿練習器
然而由於"homography.xml"(相機至投影機的轉換矩陣)已經遺失,已無法運行此檔案, 除非重新量測一次轉換矩陣

開發環境
IDE:visual studio 2012
OpenCV2