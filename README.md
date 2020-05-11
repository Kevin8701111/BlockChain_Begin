# BlockChain_Begin

## Day1
 
今天2020/05/09 跟快一年沒聯絡 我的大學長 <<旺哥>> ! ! ![](https://i.imgur.com/Day30qo.png)
傳送了這張的截圖 , 因為他是第一個教我nodejs 的學長 , 所以我沒臉在學好node之前跟旺哥聯絡QQ , 學長非常熱情的給我非常多 Blockchain的資訊 , 因為我跟他說 部屬 架構 智能合約 我全都要！！

###### 能遇到不藏招的學長姊真是三生有幸

那就開始我的Blockchain 之路了 , 首先呢 我找到
 https://ithelp.ithome.com.tw/users/20120131/ironman/2410 這位貢獻智慧的"blu3cat3803" 
 第一篇 本篇重點
 https://ithelp.ithome.com.tw/articles/10216513
 ```
 區塊鏈基礎技術
 區塊鏈的基礎一定就是密碼學
 區塊鏈的數據系統，網路層和最重要的共識以及獎勵機制
 ```
```
比特幣 - 區塊鏈技術
乙太幣 - 智能合約
```
另外的教材
https://codertw.com/%E7%A8%8B%E5%BC%8F%E8%AA%9E%E8%A8%80/419635/
```
RSA 加密法
非對稱式密碼系統的一種
利用公開金鑰密碼系統作為資料加密的方式，可達 到資料加密及數
位簽署的功能
使用對方公開金鑰(Public Key)將明文加密
RSA 解密演算法，必須使用自己的私有金鑰(Private Key)才
能將密文解出

2個值數p和q(非常大至少100位數)
N = p*q
example :公鑰
        p = 5 q = 7 e = 11 求d
        
        公鑰 = (11,35)
        4x6 = 24 在小於24中找出互質數 e = 11
        私讑 = 11xd = 1 mod 24
        d = 14 , (11x14)145 與 (24x6)144 差 1
        自訂 M = 3 , M = 未加密的資料
        加密 = C = M的e次方 mod N = 3的11次方 mod 35
            = 177147 mod 35 = 12
        解密 = M = C的d次方 mod N = 12的14次方mod 35
            = 1.2839185e+15 mod 35 = 25
        

```
RSA flask 實做(參考 https://ithelp.ithome.com.tw/articles/10215558)
