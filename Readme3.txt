今回は肌色の色摘出を行った。これを利用することにより、カメラ映像から人の肌の部分をわかりやすく
表示できるようになった。肌色の部分を白、それ以外の部分を黒に表示することにより、肌以外の箇所
である目や口などは黒く表示されるため輪郭などもわかりやすくなっている。さらに肌色の服はあまりないと考えると、
服の部分も黒く表示されるため、より肌の部分がわかりやすくなっている。
今回はサイトhttps://algorithm.joho.info/programming/python/opencv-color-tracking-py/
を参考にさせてもらった。
ここはカラー追跡するコードであるが、それだけだと特別な要素がないので、肌色を摘出できる
ようにし、その肌色からどこに人がいるかなどもわかるようになる。

コードの説明
hsv = cv2.cvtColor(img, cv2.COLOR_BGR2HSV)により、画像をhsv変換している
hsv_min = np.array([0,58,88])
hsv_max = np.array([30,255,255])これにより肌色を摘出するように変換した
cv2.imshow("camera", frame)
cv2.imshow("hadairo", mask)ここで元の映像と、変換後の白黒画像を表示している
if cv2.waitKey(25) & 0xFF == ord('q'):qが押されるとウィンドウを閉じる

実践動画
https://www.youtube.com/watch?v=0JHKv62nxCo



