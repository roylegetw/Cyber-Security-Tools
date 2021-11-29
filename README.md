# tools

### 資訊與網路安全工具

### 多編程框架
1.  [Metasploit](https://www.metasploit.com/) - 用於檢測網路漏洞以及管理安全的軟體工具。
2.  [Faraday](https://github.com/infobyte/faraday) - 集成多用戶滲透測試環境，供紅隊執行合作滲透測試、安全審計和風險評估。
3.  [AutoSploit](https://github.com/NullArray/AutoSploit) - 自動化的大規模漏洞利用程式，使用 Shodan.io API 收集目標，並根據 Shodan 查詢選擇 Metasploit 漏洞利用模組。

### 網路漏洞掃描與滲透
2.  [Nessus](https://www.tenable.com/products/nessus-vulnerability-scanner) - 系統弱點的掃描與分析，是漏洞管理、配置和合規範的評估平台。
3.  [Vuls](https://github.com/future-architect/vuls) - 適用於 GNU/Linux 和 FreeBSD 的無代理漏洞掃描程序，用 Go 語言編寫。
4.  [Nexpose](https://www.rapid7.com/products/nexpose/) - 與 Metasploit 集成的商業漏洞和風險管理評估引擎。
5.  [OpenVAS](http://www.openvas.org/) - 開源的弱點檢測管理平台，提供漏洞掃描和漏洞管理的多種服務和工具的軟體框架。
6.  [Netsparker Application Security Scanner](https://www.netsparker.com/) - 能自動發現安全漏洞的應用安全掃描工具。
7.  [Nikto](https://cirt.net/nikto2) - 開源的（GPL）網頁伺服器掃描工具，它可以對網頁伺服器進行全面的多種掃描。
8.  [Wapiti](http://wapiti.sourceforge.net/) - 是 Kali linux 和 Parrot Security OS 內建的工具，可以使用這個工具來進行 web-application 漏洞掃描。
9.  [SecApps](https://secapps.com/) - 瀏覽器內 Web 應用程序之安全測試軟體。
10. [WPScan](https://wpscan.org/) - 是一個掃描 WordPress 漏洞的黑盒子掃描工具，可為掃描 WordPress 漏洞並在開發前找到並解決問題。
11. [joomscan](https://www.owasp.org/index.php/Category:OWASP_Joomla_Vulnerability_Scanner_Project) - 是 Kali linux和 Parrot Security OS 內建的工具，可以使用這個工具來進行Joomla漏洞掃描。
12. [SQLmate](https://github.com/UltimateHackers/sqlmate) - 是一個確認網站是否有SQLi漏洞的工具。
13. [Burp Suite](https://portswigger.net/burp/) - 是一個用於測試網絡應用程式安全性的圖形化工具。該工具使用Java編寫，由PortSwigger Web Security開發。 
14. [w3af](http://w3af.org/) - 是一個開源的Web應用程式安全掃描器。該項目為Web應用程式提供了一個漏洞掃描器和漏洞利用工具。它提供了有關安全性漏洞的信息，以便在滲透測試項目中使用。

### 靜態程式分析
[cppcheck](http://cppcheck.sourceforge.net/) - 是開放源碼的靜態分析工具，可檢查出程式中是否有記憶體洩漏、未初始的變數或是存取位置超出範圍等影響安全問題。
[bandit](https://pypi.python.org/pypi/bandit/) - 檢查 python 中常見安全問題的工具。

### 網路偵測工具
[zmap](https://zmap.io/) - 開源的安全掃描程式，能夠發現漏洞及其影響，並檢測受影響的物聯網設備。
[nmap](https://nmap.org/) - 用於網路探測和安全審計的網路安全工具。
[snort](https://www.snort.org/) - 是一套開放原始碼的網路入侵預防軟體與網路入侵檢測軟體。Snort使用了以偵測簽章與通訊協定的偵測方法。

### 網路封包偵測與分析工具 
[Wireshark](https://www.wireshark.org/) - 免費開源的網路封包分析軟體，是廣泛使用的圖形化、跨平台網路協議分析工具。
[tcpdump/libpcap](http://www.tcpdump.org/) - 是 Unix/Linux 平臺下的網路封包捕獲函式庫。為底層網路監測提供了一個可移植的框架。
[Netzob](https://github.com/netzob/netzob) - 可用於對通訊協議進行逆向工程、建模和模糊測試。
[sniffglue](https://github.com/kpcyrd/sniffglue) - 使用Rust開發的網路嗅探工具(sniff)，該工具使用了執行緒池來利用所有的CPU核心並對多個網路資料包同時進行解析處理。
[tcpdump](https://www.tcpdump.org/manpages/tcpdump.1.html) - 是一個執行在命令行下的封包剖析器。它允許使用者攔截和顯示傳送或收到過網路連接到該電腦的TCP/IP和其他封包。
[Hping](http://www.hping.org/) - 是由Salvatore Sanfilippo創建的TCP / IP協議的開源封包生成器和分析器。它是用於防火牆和網絡的安全審核和測試的常用工具之一，現已整合在nmap中。
[Scapy](https://scapy.net/) - 是一種用於計算機網絡的數據包處理工具，由Philippe Biondi用Python編寫。它可以偽造或解碼數據包，通過網絡發送它們，捕獲它們，並匹配請求和響應。

### 密碼測試與破解工具
[John the Ripper](https://www.openwall.com/john/) - 是一個免費的密碼破解工具，可以自動檢測密碼的雜湊值類型並包括可自定義的破解程序。可針對各種加密的密碼格式運行。
[thc hydra](https://github.com/vanhauser-thc/thc-hydra) - 是一個網路登錄破解程式，通過使用不同的方法來執行暴力攻擊，以猜測正確的用戶名和密碼組合。

### 代理和中間人工具
[Ettercap](http://www.ettercap-project.org) - 免費的開源網絡安全工具，用於對LAN進行中間人攻擊。可用於計算機網絡協議分析和安全審核。可在各種類Unix操作系統（包括Linux，Mac OS等）以及Windows上運行。

### 無線網路工具
[Aircrack-ng](http://www.aircrack-ng.org/) - 是一個與802.11標準的無線網路分析有關的安全軟體，主要功能有：網路偵測，封包嗅探，WEP和WPA/WPA2-PSK破解。
