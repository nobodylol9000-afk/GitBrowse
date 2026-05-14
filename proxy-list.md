# Proxy List

این فایل توسط workflow شماره ۵ ساخته شده است.

> مقدار `ping_ms` زمان رفت‌وبرگشت یک درخواست HTTP/HTTPS از داخل GitHub Actions از مسیر همان proxy است؛ ICMP ping نیست.

## Fastest proxies

| Rank | PROXY_SERVER | PROXY_USERNAME | PROXY_PASSWORD | ping_ms | protocol | status | observed_ip | source |
|---:|---|---|---|---:|---|---:|---|---|
| 1 | `http://198.199.86.11:3128` | `` | `` | 359 | `http` | 200 | `198.199.86.11` | `https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt` |
| 2 | `http://86.104.72.220:1082` | `` | `` | 406 | `http` | 200 | `86.104.72.220` | `https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt` |
| 3 | `http://217.76.245.80:999` | `` | `` | 563 | `http` | 200 | `217.76.245.80` | `https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt` |
| 4 | `http://45.13.185.217:3128` | `` | `` | 760 | `http` | 200 | `45.13.185.217` | `https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/proto...` |
| 5 | `http://134.209.29.120:3128` | `` | `` | 773 | `http` | 200 | `134.209.29.120` | `https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt` |
| 6 | `http://194.59.247.34:10808` | `` | `` | 889 | `http` | 200 | `194.59.247.34` | `https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt` |
| 7 | `http://45.140.147.155:1082` | `` | `` | 987 | `http` | 200 | `45.140.147.155` | `https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt` |
| 8 | `http://162.255.110.107:8080` | `` | `` | 1117 | `http` | 200 | `104.36.233.5` | `https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt` |
| 9 | `http://87.120.222.214:444` | `` | `` | 1354 | `http` | 200 | `87.120.222.214` | `https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt` |
| 10 | `http://160.19.19.9:8080` | `` | `` | 1413 | `http` | 200 | `160.19.19.9` | `https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt` |

## استفاده در workflow شماره ۴

در workflow `🌐 4-Browse the Web` مقدار `proxy_mode` را روی `fastest-from-file` بگذارید تا ردیف اول همین فایل استفاده شود. برای انتخاب ردیف دیگر، `proxy_mode=rank-from-file` و `proxy_list_rank` را برابر شماره ردیف جدول بگذارید.

فایل ماشینی متناظر: `proxy-list.json`
