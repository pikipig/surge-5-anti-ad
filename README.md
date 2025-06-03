<p align="center">
<img src="https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/pic/surge.jpg" width="260"></img>
</p>
<div align="center">
  <a href="https://apps.apple.com/us/app/surge-5/id1442620678">
    <img src="https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/refs/heads/main/pic/appstore.png" width="220" height="75" />
  </a>
</div>
<div>
  
## 簡介
使用 GitHub Actions 自動轉換 oisd blocklist 至 Surge 5 可使用的 Domain set 格式，每3小時更新一次。

oisd 官網：https://oisd.nl/

| list 	| 用途 	|
| ------------------------------------|:------------------:	                    |
| oisd small 	| 專注於阻擋廣告 	                                                |
| oisd big 	  | 阻擋廣告、釣魚連結、惡意軟體、間諜程式、勒索軟體及網頁分析/追蹤等...|
| oisd nsfw 	| 阻擋成人內容及血腥內容 	| 

注意：oisd big 與 nsfw 已包含 oisd small 規則，不建議同時使用。

## 連結
DOMAIN-SET-small：
https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/antiAD-set-small.txt

DOMAIN-SET-big：
https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/antiAD-set-big.txt

DOMAIN-SET-nsfw：
https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/antiAD-set-nsfw.txt

### 使用方式

更新：Surge 5.100.0 (3345) 之後版本可使用 pre-matching 功能，依個人需求可自行添加。

關於 Surge 的使用方法，請見[官方手冊](https://manual.nssurge.com)。要想使用本項目的域名集，只需要在 Surge 配置文件中添加以下規則：

DOMAIN-SET-small：
```
[Rule]
DOMAIN-SET,https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/antiAD-set-small,REJECT,pre-matching
```
DOMAIN-SET-big：
```
[Rule]
DOMAIN-SET,https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/antiAD-set-big.txt,REJECT,pre-matching
```
DOMAIN-SET-nsfw：
```
[Rule]
DOMAIN-SET,https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/antiAD-set-nsfw.txt,REJECT,pre-matching
```
</div>
