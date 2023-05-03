# Origin-IP-Finder

- **Available Search engine support**
  - **[Shodan](https://www.shodan.io)**
  - **[Censys](https://search.censys.io)**
  - **[Zoomeye](https://www.zoomeye.org)**
  
# Installation
```
git clone https://github.com/rix4uni/Origin-IP-Finder.git
cd Origin-IP-Finder
chmod +x oif
mv oif /usr/bin/
```

# Setup

shodan api is `paid` and setup is `optional` but if want good results please setup...

```
shodan init SHODAN_API_KEY
```
  
# Usage
  
```
oif -d domain.com -c CENSYS_API_ID:CENSYS_API_SECRET -z ZOOMEYE_API
```
