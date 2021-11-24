# Pixelation
３Dをピクセル化してドット風のグラフィックにしたいプロジェクト<br>

## 20211123
ポストエフェクトでピクセル化<br>
ピクセル化はできても周りに黒いOutlineがない<br>
![211123Pixelation](https://user-images.githubusercontent.com/36768869/143039397-7fc8f830-3e2d-4f58-bb4b-2109519d9b56.gif)


## 20211124
Outlineを作ってからピクセル化したいのでアウトラインシェーダ書いた<br>
![image](https://user-images.githubusercontent.com/36768869/143262436-67aa3eae-9fe1-4219-912d-dbf74067d93d.png)


アウトラインシェーダにピクセル化のポストエフェクトかけてみたが、だめだった<br>
![image](https://user-images.githubusercontent.com/36768869/143262964-875e03f8-a9cf-4bdb-9a1f-6d5f5cfe8087.png)



Outlineが頂点や辺のところで綺麗にならないのでアウトラインポストエフェクトをやる。<br>
参考（https://qiita.com/Shinoda_Naoki/items/734fee861fe8abfca228#%E3%82%B3%E3%83%BC%E3%83%89%E3%81%AE%E8%AA%AC%E6%98%8E)<br>
![image](https://user-images.githubusercontent.com/36768869/143259904-a9400ca9-6723-4f3c-8c49-78af62d949cf.png)

