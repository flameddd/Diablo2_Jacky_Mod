# Diablo2_Jacky_Mod (單機 mod)

平衡性測試中

## 角色建議
- 因為怪物變很多，所以一定需要範圍招式。只練單體招，估計會很痛苦...
- 某些職業比較好清怪，可以考慮搭配 `/players8` 調整難度

## 特點
- **不改任何**怪物、角色技能、武器強度
- 增加怪物數量（4 到 10 倍）（地獄數量最多）
- 增加怪物掉落物品數量
  - 怪物不掉落 gold
  - 怪物不掉落 紅、藍水，只掉大紫
    - 一來掉落物品多，紅、藍很亂、很難整理
    - 二來後期應該也有需要，所以直接選掉大紫
- 升級經驗值 1/10
- 天梯符文組
- **阿卡拉**賣符紋、完美寶石
- 賭博戒指、項鍊 1 元
- 調整賭博機率，更容易出現黃裝、金裝、綠裝
- 商人百倍價格收購物品
  - 沒錢就去買東西、然後賣掉
    - 按住 `shift` 買 12 隻 key (買好幾組)，然後賣掉
  - 有幾萬塊後，去賭博，然後賣掉(最快)

## todo
- 掉落物品調整、只掉紫水
- 傳送門傳送牛、紅門?


## 使用前
- 先備份自己單機角色檔案

## 使用方法
1. download 這個 repo (右上方**綠色clone** -> **Download Zip**)
2. 把 `data/global/excel/` 裡面的所有檔案，放到 `\Diablo II\data\global\excel` 位置去
    - e.x. `\Diablo II\data\global\excel\levels.txt`
    - 沒有 data, global, excel 資料夾的話，自己建立就好
3. 把「暗黑的執行檔」傳送到「桌面建立捷徑」
    - 到桌面上的捷徑按右鍵 → 內容 → **目標**
    - 空一格後輸入 ` -direct -txt`
    - e.x. `"C:\Program Files (x86)\Diablo II\Diablo II.exe" -w -direct -txt`
    - （如果你以前有設定過，發現無法生效的話，就移除「`-direct -txt`」，套用，然後再加回去一次）

TODO: 附圖

## 自己動手改
- 修改資訊可以參考這篇
- 或者，這個 repo，我刻意 commit 中文 message，也可以參考看看

## 懶得自己重練，就下載人家準備好的角色存檔吧
- 易牙居各種職業、各種 build 單機角色存檔 http://iyazero.tw/download.htm
  - (易牙居首頁 http://iyazero.tw/Default.htm )
