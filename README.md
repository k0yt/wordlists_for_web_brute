# wordlists_for_web_brute
This repository contains wordlists for brute-forcing paths and files during web penetration testing.

# How to use

**Warning**:

All wordlists have lines that don't start with /, **so when brute-forcing, specify a URL like: `https://some.com/`**. Otherwise, your tool may start substituting values ​​for the TLD-part=)

**Structure**:

+ `Files` — Contains wordlists for brute-forcing files with specific extensions.
+ `all.txt` — Contains almost everything from all the wordlists listed below. Roughly speaking, this is the most complete wordlist you can run and be confident that something will definitely be found.
+ `api.txt` — Contains all `api/*` and `*/api/*` paths from popular wordlists.
+ `bitrix_final.txt` — Contains all paths from all wordlists, materials, etc. related to Bitrix.
+ `popular.txt` — Contains paths/files that frequently appear across multiple wordlists. This wordlist can be used when you need to brute-force without sending 100,000+ requests.

# Based on
+ https://github.com/danielmiessler/SecLists/tree/master/Discovery/Web-Content
+ https://github.com/sorokinpf/cth_wordlists
+ https://github.com/Averroes/raft/tree/master/data/wordlists
+ https://github.com/kkrypt0nn/wordlists/tree/main/wordlists/discovery
+ https://github.com/Bo0oM/fuzz.txt
+ https://wordlists.assetnote.io/
+ https://github.com/TheKingOfDuck/fuzzDicts
+ https://github.com/clem9669/weblist
+ https://github.com/hxlxmj/leaky-paths
+ https://github.com/3ndG4me/KaliLists/tree/master/dirb
+ https://github.com/xajkep/wordlists/tree/master/discovery
+ https://github.com/chrislockard/api_wordlist
+ https://github.com/koaj/aws-s3-bucket-wordlist/blob/master/list.txt
+ https://gist.github.com/hax0rgb/505b5de6be0a78fbd9dd0f46efbe754d
+ https://gist.github.com/vijay922/d35cf2f5c9abe682140379e35d5cd935
+ https://raw.githubusercontent.com/onvio/wordlists/master/words_and_files_top5000.txt
+ https://github.com/jivoi/pentest/tree/master/wordlists
+ https://github.com/empty-jack/YAWR
+ https://gist.github.com/Bo0oM/5d18e56847d2b1722bf5eedea853119b
+ https://pentestnotes.ru/images/notes/bitrix_full/huitix_wordlist.zip
+ https://github.com/HiMiC/bitrix_scan/blob/main/bitrix_wordlist.txt
+ https://github.com/HiMiC/bitrix_scan/tree/main
+ https://t.me/webpwn/345
+ https://t.me/webpwn/317

# Author
By ArroizX (Evgeny Kopytin)

# Links
https://t.me/ArroizX_Notes/96

# Contacts 
Telegram - @ArroizX
