<h6 align="center">Shodan + ExploitDB + GitHub + NVD</h6>
<h1 align="center"><img width="40" src=https://upload.wikimedia.org/wikipedia/commons/thumb/1/10/Shodan_logo.webp/965px-Shodan_logo.webp.png>Shotrack</h1>

Project ini adalah alat untuk menganalisis keamanan IP dan Domain menggunakan API Shodan.io. Skrip ini mengumpulkan informasi tentang IP dan Domain, mengidentifikasi potensi kerentanan terkait versi teknologi yang dipetakan oleh Shodan, dan melakukan pencarian CVE di basis data NVD dan ExploitDB. Selain itu, proyek ini mencari Proof of Concepts (PoC) dari CVE di GitHub.








### Features
+ Collection of information about IPs and Domains using the Shodan.io API.
+ Identification of vulnerabilities based on mapped technology versions.
+ Querying of CVEs in the NVD and ExploitDB databases.
+ Simple and easy-to-use interface.



### Help
<img width="700" src=https://i.ibb.co.com/HG42K4Y/shotrack.png align="center">


### Install

        git clone https://github.com/andrisecops/shotrack.git

        pip3 install -r requirements.txt

        python3 main.py --xdbupdate
        
#### Requirements
        
+ shodan
+ cve_searchsploit
+ ipcalc
+ ipaddress
+ requests
+ argparse
        
##### Get your API Shodan - https://account.shodan.io/
##### Insert your API Shodan in API.txt
