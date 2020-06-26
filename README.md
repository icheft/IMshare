# IM 1010 Final Project Grading System (IMshare)

## Notice
(Update 6/21)

請使用助教提供的main.cpp([link](https://drive.google.com/file/d/1flSE5iz6B0bDAKcv2t0MwtqLqQqqNbuM/view?usp=sharing))，之前這裡提供的暫時不再更新。

## How to Use?
1. [Download this repo](https://github.com/icheft/IMshare/archive/v1.0.4.zip).
2. 將助教給的 `Main.cpp` 替換成這個 `main.cpp` (原本的沒辦法偵測多於一個食物+不明所以地冗，雖然我也沒改多少啦)
3. 將 `mapGenerator.cpp` 放到 `/map/maps` 資料夾

For **Mac** users only (for **Windows** users, please check [here](https://github.com/desk2000/IMshare) out):  
(Make sure you are in the `/map/maps` directory!)

1. 編譯 `mapGenerator.cpp`: `g++ -std=c++11 mapGenerator.cpp -o mapGenerator.out`
2. 執行: `./mapGenerator.out`


## Result
`maps` 資料夾應該會出現 100 個新的檔案 (e.g. map_101 ~ map_200)


接下來就跟之前一樣的做法啦，有問題直接在 [issue page](https://github.com/icheft/IMshare/issues) 提出！感恩。

2020-06-11 @desk2000 and @icheft
