<p align="center">
<img src="https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/pic/surge.jpg" width="300"></img>
</p>

# 簡介
使用 GitHub Actions 自動轉換oisd small至surge 5可使用domain set格式 每6小時更新一次

oisd：https://oisd.nl/

DOMAIN-SET：
https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/antiAD-set.txt

### 使用方式

關於 Surge 的使用方法，請見[官方手冊](https://manual.nssurge.com)。要想使用本项目的域名集，只需要在 Surge 配置文件中添加以下規則：

```
[Rule]
DOMAIN-SET,https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/antiAD-set.txt,REJECT
```
