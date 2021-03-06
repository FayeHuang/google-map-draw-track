# 繪製行車軌跡

用 Google map snap to roads API 把多點座標 mapping 到道路上，繪製行車軌跡。

demo page : https://fayehuang.github.io/google-map-draw-track/

## 使用方法
 
1.  開啟 demo page
2.  在右上方欄位輸入多個座標，輸入的資料格式為 __*latitude1,longitude1<\n>latitude2,longitude2*__ <br>![id](https://cloud.githubusercontent.com/assets/10685745/17130638/25ca2bd0-534c-11e6-99bc-d2f528237838.png)
3.  按下繪製軌跡按鈕，將會根據這些座標，在地圖上畫出行車軌跡。<br>![id](https://cloud.githubusercontent.com/assets/10685745/17130641/2fd26c6e-534c-11e6-97ef-cf11a76fa81c.png)

## 使用限制

*  snap to roads API 一次最多可根據 100 個座標計算出行車軌跡
*  如果提供座標距離太遠無法算出行車軌跡
*  沒啟用付費的 google map api key 一天可以被存取 2500 次 (畫 2500 次行車軌跡)

## 參考資料

*  [Google Maps Roads API 簡介](https://developers.google.com/maps/documentation/roads/intro?hl=zh-tw)
*  [Google Maps Roads API 使用方法](https://developers.google.com/maps/documentation/roads/snap?hl=zh-tw)
