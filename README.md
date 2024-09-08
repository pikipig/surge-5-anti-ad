<p align="center">
<img src="https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/pic/surge.jpg" width="300"></img>
</p>

# 簡介
使用 GitHub Actions 自動轉換 oisd small以及big 至 Surge 5 可使用 Domain set 格式 每6小時更新一次

oisd small：https://small.oisd.nl/domainswild

oisd big：https://big.oisd.nl/domainswild

oisd nsfw：https://nsfw.oisd.nl/domainswild

DOMAIN-SET-small：
https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/antiAD-set.txt

DOMAIN-SET-big：
https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/antiAD-set-big.txt

DOMAIN-SET-nsfw：
https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/antiAD-set-nsfw.txt

### 使用方式

關於 Surge 的使用方法，請見[官方手冊](https://manual.nssurge.com)。要想使用本項目的域名集，只需要在 Surge 配置文件中添加以下規則：

DOMAIN-SET-small：
```
[Rule]
DOMAIN-SET,https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/antiAD-set.txt,REJECT
```
DOMAIN-SET-big：
```
[Rule]
DOMAIN-SET,https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/antiAD-set-big.txt,REJECT
```
DOMAIN-SET-nsfw：
```
[Rule]
DOMAIN-SET-nsfw：DOMAIN-SET,https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/antiAD-set-nsfw.txt,REJECT
```
