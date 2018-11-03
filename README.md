# wapiti [![](https://images.microbadger.com/badges/version/jorgeandrada/wapiti:latest.svg)](https://microbadger.com/images/jorgeandrada/wapiti:latest "Get your own version badge on microbadger.com") [![](https://images.microbadger.com/badges/image/jorgeandrada/wapiti:latest.svg)](https://microbadger.com/images/jorgeandrada/wapiti:latest "Get your own image badge on microbadger.com") [![](https://images.microbadger.com/badges/commit/jorgeandrada/wapiti:latest.svg)](https://microbadger.com/images/jorgeandrada/wapiti:latest "Get your own commit badge on microbadger.com")

Latest [Wapiti scan]( http://wapiti.sourceforge.net/)

<a href='https://ko-fi.com/A417UXC'><img height='36' style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi2.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

**Usage:**
```
docker run --rm -it jorgeandrada/wapiti "https://andradaprieto.es/"
#with reports
docker run --rm -it -v $(pwd):/root/.wapiti/generated_report jorgeandrada/wapiti "https://andradaprieto.es/"
```

**Help:**
```
usage: wapiti [-h] [-u URL] [--scope {page,folder,domain,url}]
              [-m MODULES_LIST] [--list-modules] [-l LEVEL] [-p PROXY_URL]
              [-a CREDENTIALS] [--auth-type {basic,digest,kerberos,ntlm}]
              [-c COOKIE_FILE] [--skip-crawl] [--resume-crawl]
              [--flush-attacks] [--flush-session] [-s URL] [-x URL]
              [-r PARAMETER] [--skip PARAMETER] [-d DEPTH]
              [--max-links-per-page MAX] [--max-files-per-dir MAX]
              [--max-scan-time MINUTES] [--max-parameters MAX] [-S FORCE]
              [-t SECONDS] [-H HEADER] [-A AGENT] [--verify-ssl {0,1}]
              [--color] [-v LEVEL] [-f FORMAT] [-o OUPUT_PATH]
              [--no-bugreport] [--version]
wapiti: error: one of the arguments -u/--url --list-modules is required
Shortest way (with default options) to launch a Wapiti scan :
```
