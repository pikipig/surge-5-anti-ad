<p align="center">
<img src="https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/pic/surge.jpg" width="260"></img>
</p>
<div align="center">
  <a href="https://apps.apple.com/us/app/surge-5/id1442620678">
    <img src="https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/refs/heads/main/pic/appstore.png" width="220" height="75" />
  </a>
</div>
<div>
  
## Introduction

Automatically convert the oisd blocklist into the Domain Set format compatible with Surge 5 using GitHub Actions. Updates every 3 hours.

Official oisd website: https://oisd.nl/

| List         | Purpose                                                                 |
|--------------|-------------------------------------------------------------------------|
| oisd small   | Focused on ad blocking                                                  |
| oisd big     | Blocks ads, phishing links, malware, spyware, ransomware, tracking, etc.|
| oisd nsfw    | Blocks adult content and gore                                           |

**Note:** `oisd big` and `oisd nsfw` already include the rules from `oisd small`. It is not recommended to use them together.

## Links

**DOMAIN-SET-small:**  
https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/antiAD-set-small.txt

**DOMAIN-SET-big:**  
https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/antiAD-set-big.txt

**DOMAIN-SET-nsfw:**  
https://raw.githubusercontent.com/pikipig/surge-5-anti-ad/main/antiAD-set-nsfw.txt

### Usage

**Update:** Starting from Surge version 5.100.0 (3345), the `pre-matching` feature is supported. You can add it according to your needs.

For instructions on using Surge, please refer to the [official manual](https://manual.nssurge.com). To use the domain sets from this project, simply add the following rules to your Surge configuration file:

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
