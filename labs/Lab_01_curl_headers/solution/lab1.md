 	Лабораторная работа №1 
  

Запрос для:‍🎓 РГУПС
*курл*: curl https://rgups.ru -I -v -L -k


 ```Connected to rgups.ru (80.72.224.90) port 443      #Соединение установлено с сайтом rgups.ru по его ip и защищеному порту
* schannel: disabled automatic use of client certificate # настройки безопасности отключены, омон вроде не должен приехать
  0     0    0     0    0     0      0      0 --:--:--  0:00:01 --:--:- 			#Информация о том сколько времени занял запрос, очень шустро на самом деле						 
  0     0    0     0    0     0      0      0 --:--:--  0:00:01 --:--:-       #тоже самое что и предыдущая строка                      
  0     0    0     0    0     0      0      0 --:--:--  0:00:02 --:--:-       #почти тоже самое что и предыдущая строка                         
  -        0* using HTTP/1.x #Эта строка говорит нам о версии протокола http
> HEAD / HTTP/1.1 #Версия хттп
> Host: rgups.ru #Целевой хост
> User-Agent: curl/8.2.1 #Информация о том, кто отправил запрос
> Accept: */* #клиент готов, принять любой тип контента
>
  0     0    0     0    0     0      0      0 --:--:--  0:00:04 --:--:--     0< HTTP/1.1 200 OK
< Server: nginx/1.19.1
< Date: Thu, 28 Sep 2023 11:33:45 GMT
< Content-Type: text/html; charset=utf-8
< Connection: keep-alive
< X-Powered-By: ProcessWire CMS
< Set-Cookie: wire=d402d256807cbcc7014f7eb0054d7543; path=/; HttpOnly; SameSite=Lax
< Expires: Thu, 19 Nov 1981 08:52:00 GMT
< Cache-Control: no-store, no-cache, must-revalidate
< Pragma: no-cache
<
  0     0    0     0    0     0      0      0 --:--:--  0:00:05 --:--:--     0HTTP/1.1 200 OK
Server: nginx/1.19.1
Date: Thu, 28 Sep 2023 11:33:45 GMT
Content-Type: text/html; charset=utf-8
Connection: keep-alive
X-Powered-By: ProcessWire CMS
Set-Cookie: wire=d402d256807cbcc7014f7eb0054d7543; path=/; HttpOnly; SameSite=Lax
Expires: Thu, 19 Nov 1981 08:52:00 GMT
Cache-Control: no-store, no-cache, must-revalidate
Pragma: no-cache
```



Запрос для : GitHub
*курл*: curl https://github.com -I -v -L -k

```
* processing: https://github.com
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0*   Trying 140.82.121.4:443...
* Connected to github.com (140.82.121.4) port 443
* schannel: disabled automatic use of client certificate
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0* using HTTP/1.x
> HEAD / HTTP/1.1
> Host: github.com
> User-Agent: curl/8.2.1
> Accept: */*
>
* schannel: remote party requests renegotiation
* schannel: renegotiating SSL/TLS connection
* schannel: SSL/TLS connection renegotiated
* schannel: remote party requests renegotiation
* schannel: renegotiating SSL/TLS connection
* schannel: SSL/TLS connection renegotiated
< HTTP/1.1 200 OK
< Server: GitHub.com
< Date: Thu, 05 Oct 2023 09:09:14 GMT
< Content-Type: text/html; charset=utf-8
< Vary: X-PJAX, X-PJAX-Container, Turbo-Visit, Turbo-Frame, Accept-Language, Accept-Encoding, Accept, X-Requested-With
< content-language: en-US
< ETag: W/"f7f9d9c1a6a521b5b9a785a27db2acc7"
< Cache-Control: max-age=0, private, must-revalidate
< Strict-Transport-Security: max-age=31536000; includeSubdomains; preload
< X-Frame-Options: deny
< X-Content-Type-Options: nosniff
< X-XSS-Protection: 0
< Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
< Content-Security-Policy: default-src 'none'; base-uri 'self'; child-src github.com/assets-cdn/worker/ gist.github.com/assets-cdn/worker/; connect-src 'self' uploads.github.com www.githubstatus.com collector.github.com raw.githubusercontent.com api.githubcopilot.com api.github.com github-cloud.s3.amazonaws.com github-production-repository-file-5c1aeb.s3.amazonaws.com github-production-upload-manifest-file-7fdce7.s3.amazonaws.com github-production-user-asset-6210df.s3.amazonaws.com cdn.optimizely.com logx.optimizely.com/v1/events objects-origin.githubusercontent.com *.actions.githubusercontent.com productionresultssa0.blob.core.windows.net/ productionresultssa1.blob.core.windows.net/ productionresultssa2.blob.core.windows.net/ productionresultssa3.blob.core.windows.net/ productionresultssa4.blob.core.windows.net/ productionresultssa5.blob.core.windows.net/ productionresultssa6.blob.core.windows.net/ productionresultssa7.blob.core.windows.net/ productionresultssa8.blob.core.windows.net/ productionresultssa9.blob.core.windows.net/ wss://*.actions.githubusercontent.com github-production-repository-image-32fea6.s3.amazonaws.com github-production-release-asset-2e65be.s3.amazonaws.com insights.github.com wss://alive.github.com github.githubassets.com; font-src github.githubassets.com; form-action 'self' github.com gist.github.com objects-origin.githubusercontent.com; frame-ancestors 'none'; frame-src viewscreen.githubusercontent.com notebooks.githubusercontent.com support.github.com; img-src 'self' data: github.githubassets.com media.githubusercontent.com camo.githubusercontent.com identicons.github.com avatars.githubusercontent.com github-cloud.s3.amazonaws.com objects.githubusercontent.com secured-user-images.githubusercontent.com/ user-images.githubusercontent.com/ private-user-images.githubusercontent.com opengraph.githubassets.com github-production-user-asset-6210df.s3.amazonaws.com customer-stories-feed.github.com spotlights-feed.github.com objects-origin.githubusercontent.com *.githubusercontent.com; manifest-src 'self'; media-src github.com user-images.githubusercontent.com/ secured-user-images.githubusercontent.com/ private-user-images.githubusercontent.com github-production-user-asset-6210df.s3.amazonaws.com github.githubassets.com; script-src github.githubassets.com; style-src 'unsafe-inline' github.githubassets.com; upgrade-insecure-requests; worker-src github.com/assets-cdn/worker/ gist.github.com/assets-cdn/worker/
< Set-Cookie: _gh_sess=Pl5E2Yq2XsZz%2Bd7j5k5OAR1REUpRRN5543lTxdb6lP4bSV0gnxjKFAgg%2F%2FTwfskz27gSdZWv7sL9qPvCKtNt%2BgIwW0mL3H%2FL8wLmxIw28ttaQX5VvqGyM7M7Zkd%2Fje7t%2BlHWcrB8dHvbsUQ3mzZjjWTgNlcn33RXWTLV%2FT0QX4C9Ik%2Bj6yeCx%2B50Sb8qq7z%2FFkA2dcs2hrU%2FwKadXqHoizwRB%2FOSvXUeZCSpWWgD76pagcFPBOmPzPgMFdw%2FxkhBB2ygYNr2GmHBSLSusxELAg%3D%3D--xru0ubA7Zx8JSiEY--sItIFvClHLqac9Vx5QHlgw%3D%3D; Path=/; HttpOnly; Secure; SameSite=Lax
< Set-Cookie: _octo=GH1.1.1162275048.1696496961; Path=/; Domain=github.com; Expires=Sat, 05 Oct 2024 09:09:21 GMT; Secure; SameSite=Lax
< Set-Cookie: logged_in=no; Path=/; Domain=github.com; Expires=Sat, 05 Oct 2024 09:09:21 GMT; HttpOnly; Secure; SameSite=Lax
< Accept-Ranges: bytes
< X-GitHub-Request-Id: F64B:A497:261FDFA:26BBF12:651E7D41
<
  0     0    0     0    0     0      0      0 --:--:--  0:00:01 --:--:--     0HTTP/1.1 200 OK
Server: GitHub.com
Date: Thu, 05 Oct 2023 09:09:14 GMT
Content-Type: text/html; charset=utf-8
Vary: X-PJAX, X-PJAX-Container, Turbo-Visit, Turbo-Frame, Accept-Language, Accept-Encoding, Accept, X-Requested-With
content-language: en-US
ETag: W/"f7f9d9c1a6a521b5b9a785a27db2acc7"
Cache-Control: max-age=0, private, must-revalidate
Strict-Transport-Security: max-age=31536000; includeSubdomains; preload
X-Frame-Options: deny
X-Content-Type-Options: nosniff
X-XSS-Protection: 0
Referrer-Policy: origin-when-cross-origin, strict-origin-when-cross-origin
Content-Security-Policy: default-src 'none'; base-uri 'self'; child-src github.com/assets-cdn/worker/ gist.github.com/assets-cdn/worker/; connect-src 'self' uploads.github.com www.githubstatus.com collector.github.com raw.githubusercontent.com api.githubcopilot.com api.github.com github-cloud.s3.amazonaws.com github-production-repository-file-5c1aeb.s3.amazonaws.com github-production-upload-manifest-file-7fdce7.s3.amazonaws.com github-production-user-asset-6210df.s3.amazonaws.com cdn.optimizely.com logx.optimizely.com/v1/events objects-origin.githubusercontent.com *.actions.githubusercontent.com productionresultssa0.blob.core.windows.net/ productionresultssa1.blob.core.windows.net/ productionresultssa2.blob.core.windows.net/ productionresultssa3.blob.core.windows.net/ productionresultssa4.blob.core.windows.net/ productionresultssa5.blob.core.windows.net/ productionresultssa6.blob.core.windows.net/ productionresultssa7.blob.core.windows.net/ productionresultssa8.blob.core.windows.net/ productionresultssa9.blob.core.windows.net/ wss://*.actions.githubusercontent.com github-production-repository-image-32fea6.s3.amazonaws.com github-production-release-asset-2e65be.s3.amazonaws.com insights.github.com wss://alive.github.com github.githubassets.com; font-src github.githubassets.com; form-action 'self' github.com gist.github.com objects-origin.githubusercontent.com; frame-ancestors 'none'; frame-src viewscreen.githubusercontent.com notebooks.githubusercontent.com support.github.com; img-src 'self' data: github.githubassets.com media.githubusercontent.com camo.githubusercontent.com identicons.github.com avatars.githubusercontent.com github-cloud.s3.amazonaws.com objects.githubusercontent.com secured-user-images.githubusercontent.com/ user-images.githubusercontent.com/ private-user-images.githubusercontent.com opengraph.githubassets.com github-production-user-asset-6210df.s3.amazonaws.com customer-stories-feed.github.com spotlights-feed.github.com objects-origin.githubusercontent.com *.githubusercontent.com; manifest-src 'self'; media-src github.com user-images.githubusercontent.com/ secured-user-images.githubusercontent.com/ private-user-images.githubusercontent.com github-production-user-asset-6210df.s3.amazonaws.com github.githubassets.com; script-src github.githubassets.com; style-src 'unsafe-inline' github.githubassets.com; upgrade-insecure-requests; worker-src github.com/assets-cdn/worker/ gist.github.com/assets-cdn/worker/
Set-Cookie: _gh_sess=Pl5E2Yq2XsZz%2Bd7j5k5OAR1REUpRRN5543lTxdb6lP4bSV0gnxjKFAgg%2F%2FTwfskz27gSdZWv7sL9qPvCKtNt%2BgIwW0mL3H%2FL8wLmxIw28ttaQX5VvqGyM7M7Zkd%2Fje7t%2BlHWcrB8dHvbsUQ3mzZjjWTgNlcn33RXWTLV%2FT0QX4C9Ik%2Bj6yeCx%2B50Sb8qq7z%2FFkA2dcs2hrU%2FwKadXqHoizwRB%2FOSvXUeZCSpWWgD76pagcFPBOmPzPgMFdw%2FxkhBB2ygYNr2GmHBSLSusxELAg%3D%3D--xru0ubA7Zx8JSiEY--sItIFvClHLqac9Vx5QHlgw%3D%3D; Path=/; HttpOnly; Secure; SameSite=Lax
Set-Cookie: _octo=GH1.1.1162275048.1696496961; Path=/; Domain=github.com; Expires=Sat, 05 Oct 2024 09:09:21 GMT; Secure; SameSite=Lax
Set-Cookie: logged_in=no; Path=/; Domain=github.com; Expires=Sat, 05 Oct 2024 09:09:21 GMT; HttpOnly; Secure; SameSite=Lax
Accept-Ranges: bytes
X-GitHub-Request-Id: F64B:A497:261FDFA:26BBF12:651E7D41


* Connection #0 to host github.com left intact
```

Запрос для : RZD
*курл*: curl www.rzd.ru -I -v -L -k --User-agent "Google"

```
processing: www.rzd.ru
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0*   Trying 212.164.138.123:80...
* Connected to www.rzd.ru (212.164.138.123) port 80
> HEAD / HTTP/1.1
> Host: www.rzd.ru
> User-Agent: Google
> Accept: */*
>
< HTTP/1.1 301 Moved Permanently
< Date: Sun, 22 Oct 2023 11:46:09 GMT
< Content-Type: text/html
< Content-Length: 150
< Connection: keep-alive
< Location: https://www.rzd.ru:443/
<
  0   150    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
* Connection #0 to host www.rzd.ru left intact
* Clear auth, redirects to port from 80 to 443
* Issue another request to this URL: 'https://www.rzd.ru:443/'
*   Trying 212.164.138.123:443...
* Connected to www.rzd.ru (212.164.138.123) port 443
* schannel: disabled automatic use of client certificate
* using HTTP/1.x
> HEAD / HTTP/1.1
> Host: www.rzd.ru
> User-Agent: Google
> Accept: */*
>
< HTTP/1.1 200
< Content-Type: text/html;charset=utf-8
< Content-Length: 206243
< Connection: keep-alive
< Date: Sun, 22 Oct 2023 11:46:09 GMT
< Vary: Accept-Encoding
< X-UCM-Pod-Name: inex-ucm-bc445bf7f-p6k8d
< Strict-Transport-Security: max-age=15724800; includeSubDomains
< Via: nginx3
< X-Frame-Options: sameorigin
< Set-Cookie: session-cookie=17906b6babd1510e103b755718991a24bc38adcaa16cfa531323c7eb1a0a8d555bc473e211fdb4a5d94b8cc1dca1a92e; Max-Age=86400; Path=/; secure; HttpOnly
< X-XSS-Protection: 1; mode=block
<
  0  201k    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0HTTP/1.1 301 Moved Permanently
Date: Sun, 22 Oct 2023 11:46:09 GMT
Content-Type: text/html
Content-Length: 150
Connection: keep-alive
Location: https://www.rzd.ru:443/

HTTP/1.1 200
Content-Type: text/html;charset=utf-8
Content-Length: 206243
Connection: keep-alive
Date: Sun, 22 Oct 2023 11:46:09 GMT
Vary: Accept-Encoding
X-UCM-Pod-Name: inex-ucm-bc445bf7f-p6k8d
Strict-Transport-Security: max-age=15724800; includeSubDomains
Via: nginx3
X-Frame-Options: sameorigin
Set-Cookie: session-cookie=17906b6babd1510e103b755718991a24bc38adcaa16cfa531323c7eb1a0a8d555bc473e211fdb4a5d94b8cc1dca1a92e; Max-Age=86400; Path=/; secure; HttpOnly
X-XSS-Protection: 1; mode=block


* Connection #1 to host www.rzd.ru left intact
```
Запрос для : Yandex
*курл*: curl www.yandex.ru -I -v -L -k --User-agent "Google"
```
 processing: www.yandex.ru
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0*   Trying 77.88.55.60:80...
* Connected to www.yandex.ru (77.88.55.60) port 80
> HEAD / HTTP/1.1
> Host: www.yandex.ru
> User-Agent: Yandex
> Accept: */*
>
< HTTP/1.1 302 Moved temporarily
< Accept-CH: Sec-CH-UA-Platform-Version, Sec-CH-UA-Mobile, Sec-CH-UA-Model, Sec-CH-UA, Sec-CH-UA-Full-Version-List, Sec-CH-UA-WoW64, Sec-CH-UA-Arch, Sec-CH-UA-Bitness, Sec-CH-UA-Platform, Sec-CH-UA-Full-Version, Viewport-Width, DPR, Device-Memory, RTT, Downlink, ECT
< Cache-Control: max-age=1209600,private
< Date: Thu, 26 Oct 2023 11:10:21 GMT
< Location: https://dzen.ru/?yredirect=true
< NEL: {"report_to": "network-errors", "max_age": 100, "success_fraction": 0.001, "failure_fraction": 0.1}
< P3P: policyref="/w3c/p3p.xml", CP="NON DSP ADM DEV PSD IVDo OUR IND STP PHY PRE NAV UNI"
< Portal: Home
< Report-To: { "group": "network-errors", "max_age": 100, "endpoints": [{"url": "https://dr.yandex.net/nel", "priority": 1}, {"url": "https://dr2.yandex.net/nel", "priority": 2}]}
< X-Content-Type-Options: nosniff
< X-Robots-Tag: unavailable_after: 12 Sep 2022 00:00:00 PST
< X-Yandex-Req-Id: 1698318621018568-280545793214650267-balancer-l7leveler-kubr-yp-sas-51-BAL-6234
< set-cookie: is_gdpr=0; Path=/; Domain=.yandex.ru; Expires=Sat, 25 Oct 2025 11:10:21 GMT
< set-cookie: is_gdpr_b=CLbVbBCe1gEoAg==; Path=/; Domain=.yandex.ru; Expires=Sat, 25 Oct 2025 11:10:21 GMT
< set-cookie: _yasc=PfrlsUxBObw/8knVJbc9lKZHA53f1s3zs3SYmKZBKMGCpXNvD6Q9NdH3bgdeEBlj; domain=.yandex.ru; path=/; expires=Sun, 23 Oct 2033 11:10:21 GMT; secure
<
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
* Connection #0 to host www.yandex.ru left intact
* Clear auth, redirects to port from 80 to 443
* Issue another request to this URL: 'https://dzen.ru/?yredirect=true'
*   Trying 62.217.160.2:443...
* Connected to dzen.ru (62.217.160.2) port 443
* schannel: disabled automatic use of client certificate
* using HTTP/1.x
> HEAD /?yredirect=true HTTP/1.1
> Host: dzen.ru
> User-Agent: Yandex
> Accept: */*
>
< HTTP/1.1 200 Ok
< Cache-Control: no-cache, no-store, max-age=0, must-revalidate
< Content-Security-Policy: frame-ancestors sq2.go.mail.ru metrika.yandex.ru webvisor.com; report-uri https://csp.yandex.net/csp?from=zen_old&project=zen&yandex_login=&yandexuid=4904390611698318621&requestid=4118215370.205.1698318621837.25102&page=site_desktop;
< Content-Security-Policy-Report-Only: default-src 'none'; connect-src 'self' an.yandex.ru strm.yandex.ru *.strm.yandex.net mc.yandex.ru yandex.st yastatic.net matchid.adfox.yandex.ru adfox.yandex.ru ads.adfox.ru ads6.adfox.ru jstracer.yandex.ru yastat.net yandex.ru awaps.yandex.net awaps.yandex.ru verify.yandex.ru *.verify.yandex.ru favicon.yandex.net pixel.adsafeprotected.com tps.doubleverify.com ad.adriver.ru amc.yandex.ru *.tunneler-si.dzen.ru *.tun.si.dzen.ru http-check-headers.yandex.ru mc.yandex.az mc.yandex.by mc.yandex.co.il mc.yandex.com mc.yandex.com.am mc.yandex.com.ge mc.yandex.com.tr mc.yandex.ee mc.yandex.fr mc.yandex.kg mc.yandex.kz mc.yandex.lt mc.yandex.lv mc.yandex.md mc.yandex.tj mc.yandex.tm mc.yandex.ua mc.yandex.uz mc.admetrica.ru yandexmetrica.com yandexmetrica.com:29009 yandexmetrica.com:30102 forms-ext-api.yandex.ru strm.yandex.net *.strm.yandex.ru *.cdn.ngenix.net zen-rc3.yandex.ru frontend.vh.yandex.ru https://vh.test.yandex.ru/live/ wss://push.yandex.ru api.passport.yandex.ru api.passport-test.yandex.ru suggest-maps.yandex.ru/suggest-geo vk.ru static.dzeninfra.ru avatars.dzeninfra.ru cdn.dzen.ru video.dzen.ru log.dzen.ru playlog.dzen.ru cdn.dzeninfra.ru *.cdn.dzeninfra.ru *.extcdn.dzeninfra.ru *.hot-video.dzeninfra.ru cold-video.dzeninfra.ru *.cold-video.dzeninfra.ru s3.dzeninfra.ru *.s3.dzeninfra.ru *.ms.dzen.ru notify.dzen.ru clck.dzen.ru static-mon.yandex.net cloud-api.yandex.ru yandex.ru dzen.ru *.adlooxtracking.com *.adlooxtracking.ru *.adsafeprotected.com *.doubleverify.com *.moatads.com *.serving-sys.com *.serving-sys.ru *.mail.ru *.mradx.net *.imgsmail.ru *.criteo.com *.criteo.net *.mycdn.me *.vkuser.net; frame-src awaps.yandex.net yandexadexchange.net *.yandexadexchange.net yastatic.net *.yandex.ru banners.adfox.ru yastat.net yandex.ru storage.mds.yandex.net *.tunneler-si.dzen.ru *.tun.si.dzen.ru http-check-headers.yandex.ru blob: mc.yandex.ru mc.yandex.md zenadservices.net sso.passport.yandex.ru id.vk.com *.dzen.ru sso.dzen.ru static.dzeninfra.ru suggest.dzen.ru 'self' yandex.ru *.mail.ru *.mradx.net *.imgsmail.ru *.criteo.com *.criteo.net *.mycdn.me *.vkuser.net *.doubleverify.com *.doubleclick.net; img-src 'self' data: avatars-fast.yandex.net favicon.yandex.net an.yandex.ru banners.adfox.ru content.adfox.ru ads6.adfox.ru tns-counter.ru *.tns-counter.ru s3.mds.yandex.net ads.adfox.ru amc.yandex.ru mc.admetrica.ru wcm-ru.frontend.weborama.fr wcm.solution.weborama.fr ad.adriver.ru bs.serving-sys.com ad.doubleclick.net counter.yadro.ru gdeby.hit.gemius.pl mc.yandex.ru verify.yandex.ru *.verify.yandex.ru yastatic.net yastat.net avatars.mds.yandex.net yandex.ru px.moatads.com awaps.yandex.net awaps.yandex.ru gdero.hit.gemius.pl pixel.adlooxtracking.com tps.doubleverify.com impression.appsflyer.com rgi.io track.rutarget.ru ssl.hurra.com pixel.adsafeprotected.com storage.mds.yandex.net *.tunneler-si.dzen.ru *.tun.si.dzen.ru http-check-headers.yandex.ru mc.yandex.az mc.yandex.by mc.yandex.co.il mc.yandex.com mc.yandex.com.am mc.yandex.com.ge mc.yandex.com.tr mc.yandex.ee mc.yandex.fr mc.yandex.kg mc.yandex.kz mc.yandex.lt mc.yandex.lv mc.yandex.md mc.yandex.tj mc.yandex.tm mc.yandex.ua mc.yandex.uz mc.webvisor.org *.mediascope.mc.yandex.ru avatars.mdst.yandex.net zen.s3.yandex.net strm.yandex.ru strm.yandex.net sso.passport.yandex.ru dzen.ru avaHTTP/1.1 302 Moved temporarily
Accept-CH: Sec-CH-UA-Platform-Version, Sec-CH-UA-Mobile, Sec-CH-UA-Model, Sec-CH-UA, Sec-CH-UA-Full-Version-List, Sec-CH-UA-WoW64, Sec-CH-UA-Arch, Sec-CH-UA-Bitness, Sec-CH-UA-Platform, Sec-CH-UA-Full-Version, Viewport-Width, DPR, Device-Memory, RTT, Downlink, ECT
Cache-Control: max-age=1209600,private
Date: Thu, 26 Oct 2023 11:10:21 GMT
Location: https://dzen.ru/?yredirect=true
NEL: {"report_to": "network-errors", "max_age": 100, "success_fraction": 0.001, "failure_fraction": 0.1}
P3P: policyref="/w3c/p3p.xml", CP="NON DSP ADM DEV PSD IVDo OUR IND STP PHY PRE NAV UNI"
Portal: Home
Report-To: { "group": "network-errors", "max_age": 100, "endpoints": [{"url": "https://dr.yandex.net/nel", "priority": 1}, {"url": "https://dr2.yandex.net/nel", "priority": 2}]}
X-Content-Type-Options: nosniff
X-Robots-Tag: unavailable_after: 12 Sep 2022 00:00:00 PST
X-Yandex-Req-Id: 1698318621018568-280545793214650267-balancer-l7leveler-kubr-yp-sas-51-BAL-6234
set-cookie: is_gdpr=0; Path=/; Domain=.yandex.ru; Expires=Sat, 25 Oct 2025 11:10:21 GMT
set-cookie: is_gdpr_b=CLbVbBCe1gEoAg==; Path=/; Domain=.yandex.ru; Expires=Sat, 25 Oct 2025 11:10:21 GMT
set-cookie: _yasc=PfrlsUxBObw/8knVJbc9lKZHA53f1s3zs3SYmKZBKMGCpXNvD6Q9NdH3bgdeEBlj; domain=.yandex.ru; path=/; expires=Sun, 23 Oct 2033 11:10:21 GMT; secure

HTTP/1.1 200 Ok
Cache-Control: no-cache, no-store, max-age=0, must-revalidate
Content-Security-Policy: frame-ancestors sq2.go.mail.ru metrika.yandex.ru webvisor.com; report-uri https://csp.yandex.net/csp?from=zen_old&project=zen&yandex_login=&yandexuid=4904390611698318621&requestid=4118215370.205.1698318621837.25102&page=site_desktop;
Content-Security-Policy-Report-Only: default-src 'none'; connect-src 'self' an.yandex.ru strm.yandex.ru *.strm.yandex.net mc.yandex.ru yandex.st yastatic.net matchid.adfox.yandex.ru adfox.yandex.ru ads.adfox.ru ads6.adfox.ru jstracer.yandex.ru yastat.net yandex.ru awaps.yandex.net awaps.yandex.ru verify.yandex.ru *.verify.yandex.ru favicon.yandex.net pixel.adsafeprotected.com tps.doubleverify.com ad.adriver.ru amc.yandex.ru *.tunneler-si.dzen.ru *.tun.si.dzen.ru http-check-headers.yandex.ru mc.yandex.az mc.yandex.by mc.yandex.co.il mc.yandex.com mc.yandex.com.am mc.yandex.com.ge mc.yandex.com.tr mc.yandex.ee mc.yandex.fr mc.yandex.kg mc.yandex.kz mc.yandex.lt mc.yandex.lv mc.yandex.md mc.yandex.tj mc.yandex.tm mc.yandex.ua mc.yandex.uz mc.admetrica.ru yandexmetrica.com yandexmetrica.com:29009 yandexmetrica.com:30102 forms-ext-api.yandex.ru strm.yandex.net *.strm.yandex.ru *.cdn.ngenix.net zen-rc3.yandex.ru frontend.vh.yandex.ru https://vh.test.yandex.ru/live/ wss://push.yandex.ru api.passport.yandex.ru api.passport-test.yandex.ru suggest-maps.yandex.ru/suggest-geo vk.ru static.dzeninfra.ru avatars.dzeninfra.ru cdn.dzen.ru video.dzen.ru log.dzen.ru playlog.dzen.ru cdn.dzeninfra.ru *.cdn.dzeninfra.ru *.extcdn.dzeninfra.ru *.hot-video.dzeninfra.ru cold-video.dzeninfra.ru *.cold-video.dzeninfra.ru s3.dzeninfra.ru *.s3.dzeninfra.ru *.ms.dzen.ru notify.dzen.ru clck.dzen.ru static-mon.yandex.net cloud-api.yandex.ru yandex.ru dzen.ru *.adlooxtracking.com *.adlooxtracking.ru *.adsafeprotected.com *.doubleverify.com *.moatads.com *.serving-sys.com *.serving-sys.ru *.mail.ru *.mradx.net *.imgsmail.ru *.criteo.com *.criteo.net *.mycdn.me *.vkuser.net; frame-src awaps.yandex.net yandexadexchange.net *.yandexadexchange.net yastatic.net *.yandex.ru banners.adfox.ru yastat.net yandex.ru storage.mds.yandex.net *.tunneler-si.dzen.ru *.tun.si.dzen.ru http-check-headers.yandex.ru blob: mc.yandex.ru mc.yandex.md zenadservices.net sso.passport.yandex.ru id.vk.com *.dzen.ru sso.dzen.ru static.dzeninfra.ru suggest.dzen.ru 'self' yandex.ru *.mail.ru *.mradx.net *.imgsmail.ru *.criteo.com *.criteo.net *.mycdn.me *.vkuser.net *.doubleverify.com *.doubleclick.net; img-src 'self' data: avatars-fast.yandex.net favicon.yandex.net an.yandex.ru banners.adfox.ru content.adfox.ru ads6.adfox.ru tns-counter.ru *.tns-counter.ru s3.mds.yandex.net ads.adfox.ru amc.yandex.ru mc.admetrica.ru wcm-ru.frontend.weborama.fr wcm.solution.weborama.fr ad.adriver.ru bs.serving-sys.com ad.doubleclick.net counter.yadro.ru gdeby.hit.gemius.pl mc.yandex.ru verify.yandex.ru *.verify.yandex.ru yastatic.net yastat.net avatars.mds.yandex.net yandex.ru px.moatads.com awaps.yandex.net awaps.yandex.ru gdero.hit.gemius.pl pixel.adlooxtracking.com tps.doubleverify.com impression.appsflyer.com rgi.io track.rutarget.ru ssl.hurra.com pixel.adsafeprotected.com storage.mds.yandex.net *.tunneler-si.dzen.ru *.tun.si.dzen.ru http-check-headers.yandex.ru mc.yandex.az mc.yandex.by mc.yandex.co.il mc.yandex.com mc.yandex.com.am mc.yandex.com.ge mc.yandex.com.tr mc.yandex.ee mc.yandex.fr mc.yandex.kg mc.yandex.kz mc.yandex.lt mc.yandex.lv mc.yandex.md mc.yandex.tj mc.yandex.tm mc.yandex.ua mc.yandex.uz mc.webvisor.org *.mediascope.mc.yandex.ru avatars.mdst.yandex.net zen.s3.yandex.net strm.yandex.ru strm.yandex.net sso.passport.yandex.ru dzen.ru avatars.dzeninfra.ru static.dzeninfra.ru cdn.dzen.ru video.dzen.ru log.dzen.ru playlog.dzen.ru s3.dzeninfra.ru *.ms.dzen.ru *.s3.dzeninfra.ru *.zen.yandex.com *.m-counter.ru www.m-counter.ru www.tns-counter.ru *.mail.ru *.mradx.net *.imgsmail.ru *.criteo.com *.criteo.net *.mycdn.me *.vkuser.net *.doubleverify.com *.adsafeprotected.com *.serving-sys.com *.serving-sys.ru *.weborama.fr *.weborama-tech.ru *.hit.gemius.pl consentmanager.mgr.consensu.org cdn.consentmanager.mgr.consensu.org *.adlooxtracking.com *.adlooxtracking.ru vk.com vk.ru *.userapi.com *.vk.com *.vk.ru; media-src *.yandex.net strm.yandex.ru *.strm.yandex.ru yandex.ru yandex.st yastatic.net banners.adfox.ru content.adfox.ru data: yastat.net *.mycdn.me *.vkuser.net *.tunneler-si.dzen.ru *.tun.si.dzen.ru http-check-headers.yandex.ru blob: *.strm.yandex.net *.cdn.ngenix.net cdn.dzen.ru video.dzen.ru *.cdn.dzeninfra.ru *.extcdn.dzeninfra.ru *.hot-video.dzeninfra.ru cold-video.dzeninfra.ru *.cold-video.dzeninfra.ru *.s3.dzeninfra.ru *.mail.ru *.mradx.net *.imgsmail.ru *.criteo.com *.criteo.net; script-src 'unsafe-inline' 'unsafe-eval' an.yandex.ru yandex.st yastatic.net mc.yandex.ru banners.adfox.ru ads.adfox.ru ads6.adfox.ru yastat.net yandex.ru z.moatads.com storage.mds.yandex.net *.tunneler-si.dzen.ru *.tun.si.dzen.ru http-check-headers.yandex.ru mc.yandex.az mc.yandex.by mc.yandex.co.il mc.yandex.com mc.yandex.com.am mc.yandex.com.ge mc.yandex.com.tr mc.yandex.ee mc.yandex.fr mc.yandex.kg mc.yandex.kz mc.yandex.lt mc.yandex.lv mc.yandex.md mc.yandex.tj mc.yandex.tm mc.yandex.ua mc.yandex.uz chat.s3.yandex.net sso.dzen.ru sso.passport.yandex.ru static.dzeninfra.ru 'self' *.zen.yandex.com dzen.ru *.mail.ru *.mradx.net *.imgsmail.ru *.criteo.com *.criteo.net *.mycdn.me *.vkuser.net *.adlooxtracking.com *.adlooxtracking.ru *.adsafeprotected.com *.doubleverify.com *.moatads.com *.dvtps.com *.doubleclick.net *.serving-sys.ru *.userapi.com vk.com vk.ru *.vk.com *.vk.ru; style-src 'unsafe-inline' 'unsafe-eval' yandex.st yastatic.net banners.adfox.ru content.adfox.ru yastat.net *.tunneler-si.dzen.ru *.tun.si.dzen.ru http-check-headers.yandex.ru yandex.ru static.dzeninfra.ru 'self' *.zen.yandex.com dzen.ru *.mail.ru *.mradx.net *.imgsmail.ru *.criteo.com *.criteo.net *.mycdn.me *.vkuser.net; font-src 'self' data: an.yandex.ru yastatic.net yastat.net *.tunneler-si.dzen.ru *.tun.si.dzen.ru http-check-headers.yandex.ru static.dzeninfra.ru *.mail.ru *.mradx.net *.imgsmail.ru *.criteo.com *.criteo.net *.mycdn.me *.vkuser.net fonts.gstatic.com; child-src blob: mc.yandex.ru; manifest-src *.dzen.ru/manifest.webmanifest 'self'; report-uri https://csp.yandex.net/csp?from=zen_old&project=zen&yandex_login=&yandexuid=4904390611698318621&requestid=4118215370.205.1698318621837.25102&page=site_desktop;
Content-Type: text/html; charset=utf-8
Set-Cookie: _yasc=kqmHPrcqGLcyz34MInMSHmpZQax4jk2kxuPxmisMdsfFKPansKnBsx8NXIPy7eAupg==; domain=.dzen.ru; path=/; expires=Sun, 23 Oct 2033 11:10:21 GMT; secure
X-Content-Type-Options: nosniff
X-Requestid: 4118215370.205.1698318621837.25102
X-XSS-Protection: 1; mode=block
X-Yandex-Req-Id: 1698318621804156-1551695060278061231400192-protars.dzeninfra.ru static.dzeninfra.ru cdn.dzen.ru video.dzen.ru log.dzen.ru playlog.dzen.ru s3.dzeninfra.ru *.ms.dzen.ru *.s3.dzeninfra.ru *.zen.yandex.com *.m-counter.ru www.m-counter.ru www.tns-counter.ru *.mail.ru *.mradx.net *.imgsmail.ru *.criteo.com *.criteo.net *.mycdn.me *.vkuser.net *.doubleverify.com *.adsafeprotected.com *.serving-sys.com *.serving-sys.ru *.weborama.fr *.weborama-tech.ru *.hit.gemius.pl consentmanager.mgr.consensu.org cdn.consentmanager.mgr.consensu.org *.adlooxtracking.com *.adlooxtracking.ru vk.com vk.ru *.userapi.com *.vk.com *.vk.ru; media-src *.yandex.net strm.yandex.ru *.strm.yandex.ru yandex.ru yandex.st yastatic.net banners.adfox.ru content.adfox.ru data: yastat.net *.mycdn.me *.vkuser.net *.tunneler-si.dzen.ru *.tun.si.dzen.ru http-check-headers.yandex.ru blob: *.strm.yandex.net *.cdn.ngenix.net cdn.dzen.ru video.dzen.ru *.cdn.dzeninfra.ru *.extcdn.dzeninfra.ru *.hot-video.dzeninfra.ru cold-video.dzeninfra.ru *.cold-video.dzeninfra.ru *.s3.dzeninfra.ru *.mail.ru *.mradx.net *.imgsmail.ru *.criteo.com *.criteo.net; script-src 'unsafe-inline' 'unsafe-eval' an.yandex.ru yandex.st yastatic.net mc.yandex.ru banners.adfox.ru ads.adfox.ru ads6.adfox.ru yastat.net yandex.ru z.moatads.com storage.mds.yandex.net *.tunneler-si.dzen.ru *.tun.si.dzen.ru http-check-headers.yandex.ru mc.yandex.az mc.yandex.by mc.yandex.co.il mc.yandex.com mc.yandex.com.am mc.yandex.com.ge mc.yandex.com.tr mc.yandex.ee mc.yandex.fr mc.yandex.kg mc.yandex.kz mc.yandex.lt mc.yandex.lv mc.yandex.md mc.yandex.tj mc.yandex.tm mc.yandex.ua mc.yandex.uz chat.s3.yandex.net sso.dzen.ru sso.passport.yandex.ru static.dzeninfra.ru 'self' *.zen.yandex.com dzen.ru *.mail.ru *.mradx.net *.imgsmail.ru *.criteo.com *.criteo.net *.mycdn.me *.vkuser.net *.adlooxtracking.com *.adlooxtracking.ru *.adsafeprotected.com *.doubleverify.com *.moatads.com *.dvtps.com *.doubleclick.net *.serving-sys.ru *.userapi.com vk.com vk.ru *.vk.com *.vk.ru; style-src 'unsafe-inline' 'unsafe-eval' yandex.st yastatic.net banners.adfox.ru content.adfox.ru yastat.net *.tunneler-si.dzen.ru *.tun.si.dzen.ru http-check-headers.yandex.ru yandex.ru static.dzeninfra.ru 'self' *.zen.yandex.com dzen.ru *.mail.ru *.mradx.net *.imgsmail.ru *.criteo.com *.criteo.net *.mycdn.me *.vkuser.net; font-src 'self' data: an.yandex.ru yastatic.net yastat.net *.tunneler-si.dzen.ru *.tun.si.dzen.ru http-check-headers.yandex.ru static.dzeninfra.ru *.mail.ru *.mradx.net *.imgsmail.ru *.criteo.com *.criteo.net *.mycdn.me *.vkuser.net fonts.gstatic.com; child-src blob: mc.yandex.ru; manifest-src *.dzen.ru/manifest.webmanifest 'self'; report-uri https://csp.yandex.net/csp?from=zen_old&project=zen&yandex_login=&yandexuid=4904390611698318621&requestid=4118215370.205.1698318621837.25102&page=site_desktop;
< Content-Type: text/html; charset=utf-8
< Set-Cookie: _yasc=kqmHPrcqGLcyz34MInMSHmpZQax4jk2kxuPxmisMdsfFKPansKnBsx8NXIPy7eAupg==; domain=.dzen.ru; path=/; expires=Sun, 23 Oct 2033 11:10:21 GMT; secure
< X-Content-Type-Options: nosniff
< X-Requestid: 4118215370.205.1698318621837.25102
< X-XSS-Protection: 1; mode=block
< X-Yandex-Req-Id: 1698318621804156-1551695060278061231400192-production-app-host-vla-zen-13
<
  0     0    0     0    0     0      0      0 --:--:--  0:00:01 --:--:--     0duction-app-host-vla-zen-13


* Connection #1 to host dzen.ru left intact
```
Запрос для : Python
*курл*: curl www.python.org -I -v -L -k --User-agent "Google"

```
processing: www.python.org
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0*   Trying 151.101.244.223:80...
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0* Connected to www.python.org (151.101.244.223) port 80
> HEAD / HTTP/1.1
> Host: www.python.org
> User-Agent: Yandex
> Accept: */*
>
< HTTP/1.1 301 Moved Permanently
< Connection: close
< Content-Length: 0
< Server: Varnish
< Retry-After: 0
< Location: https://www.python.org/
< Accept-Ranges: bytes
< Date: Thu, 26 Oct 2023 11:13:33 GMT
< Via: 1.1 varnish
< X-Served-By: cache-hel1410027-HEL
< X-Cache: HIT
< X-Cache-Hits: 0
< X-Timer: S1698318813.450220,VS0,VE0
< Strict-Transport-Security: max-age=63072000; includeSubDomains; preload
<
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
* Closing connection
* Clear auth, redirects to port from 80 to 443
* Issue another request to this URL: 'https://www.python.org/'
*   Trying 151.101.244.223:443...
  0     0    0     0    0     0      0      0 --:--:--  0:00:02 --:--:--     0* Connected to www.python.org (151.101.244.223) port 443
* schannel: disabled automatic use of client certificate
* using HTTP/1.x
> HEAD / HTTP/1.1
> Host: www.python.org
> User-Agent: Yandex
> Accept: */*
>
* schannel: remote party requests renegotiation
* schannel: renegotiating SSL/TLS connection
* schannel: SSL/TLS connection renegotiated
< HTTP/1.1 200 OK
< Connection: keep-alive
< Content-Length: 50398
< Report-To: {"group":"heroku-nel","max_age":3600,"endpoints":[{"url":"https://nel.heroku.com/reports?ts=1698315943&sid=67ff5de4-ad2b-4112-9289-cf96be89efed&s=fpODzBEWbwRdLOK6sAKa1SdEkZVGCyG4ewTYWhr07js%3D"}]}
< Reporting-Endpoints: heroku-nel=https://nel.heroku.com/reports?ts=1698315943&sid=67ff5de4-ad2b-4112-9289-cf96be89efed&s=fpODzBEWbwRdLOK6sAKa1SdEkZVGCyG4ewTYWhr07js%3D
< Nel: {"report_to":"heroku-nel","max_age":3600,"success_fraction":0.005,"failure_fraction":0.05,"response_headers":["Via"]}
< Server: nginx
< Content-Type: text/html; charset=utf-8
< X-Frame-Options: SAMEORIGIN
< Via: 1.1 vegur, 1.1 varnish, 1.1 varnish
< Accept-Ranges: bytes
< Date: Thu, 26 Oct 2023 11:13:35 GMT
< Age: 2853
< X-Served-By: cache-iad-kiad7000025-IAD, cache-hel1410029-HEL
< X-Cache: HIT, HIT
< X-Cache-Hits: 17, 33
< X-Timer: S1698318816.708848,VS0,VE0
< Vary: Cookie
< Strict-Transport-Security: max-age=63072000; includeSubDomains; preload
```
Запрос для : Saing GIT
*курл*: curl www.git-scm.com -I -v -L -k --User-agent "Google"

```
processing: www.git-scm.com
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:--  0:00:01 --:--:--     0*   Trying 188.114.99.234:80...
* Connected to www.git-scm.com (188.114.99.234) port 80
> HEAD / HTTP/1.1
> Host: www.git-scm.com
> User-Agent: Yandex
> Accept: */*
>
< HTTP/1.1 301 Moved Permanently
< Date: Thu, 26 Oct 2023 11:17:54 GMT
< Connection: keep-alive
< Cache-Control: max-age=3600
< Expires: Thu, 26 Oct 2023 12:17:54 GMT
< Location: https://www.git-scm.com/
< Server: cloudflare
< CF-RAY: 81c24ba85c431cad-FRA
<
  0     0    0     0    0     0      0      0 --:--:--  0:00:02 --:--:--     0
* Connection #0 to host www.git-scm.com left intact
* Clear auth, redirects to port from 80 to 443
* Issue another request to this URL: 'https://www.git-scm.com/'
*   Trying 188.114.99.234:443...
  0     0    0     0    0     0      0      0 --:--:--  0:00:02 --:--:--     0* Connected to www.git-scm.com (188.114.99.234) port 443
* schannel: disabled automatic use of client certificate
* using HTTP/1.x
> HEAD / HTTP/1.1
> Host: www.git-scm.com
> User-Agent: Yandex
> Accept: */*
>
* 

processing: www.jetbrains.com
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0*   Trying 13.33.243.120:80...
* Connected to www.jetbrains.com (13.33.243.120) port 80
> HEAD / HTTP/1.1
> Host: www.jetbrains.com
> User-Agent: Yandex
> Accept: */*
>
< HTTP/1.1 301 Moved Permanently
< Server: CloudFront
< Date: Thu, 26 Oct 2023 11:39:52 GMT
< Content-Type: text/html
< Content-Length: 167
< Connection: keep-alive
< Location: https://www.jetbrains.com/
< X-Cache: Redirect from cloudfront
< Via: 1.1 891326e51cae7827755c7a9147113a54.cloudfront.net (CloudFront)
< X-Amz-Cf-Pop: HEL50-C1
< Alt-Svc: h3=":443"; ma=86400
< X-Amz-Cf-Id: 8DV6_3DOurjX5ZoaJSbrXPn-JMQa739l_mU4d73VtXvpyYnBnf1_Ew==
<
  0   167    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
* Connection #0 to host www.jetbrains.com left intact
* 
< HTTP/1.1 200 OK
< Content-Type: text/html; charset=utf-8
< Content-Length: 47748
< Connection: keep-alive
< Date: Thu, 26 Oct 2023 11:35:00 GMT
< Server: nginx
< X-Content-Type-Options: nosniff
< Referrer-Policy: same-origin
< Expires: Thu, 26 Oct 2023 11:35:00 GMT
< Cache-Control: max-age=0
< Pragma: no-cache
< X-Frame-Options: DENY
< X-Content-Type-Options: nosniff
< X-Xss-Protection: 1; mode=block
< Strict-Transport-Security: max-age=31536000;
< Vary: Accept-Encoding
< Via: 1.1 79beb37803543f9a0f0aa59f238cc43a.cloudfront.net (CloudFront)
< Alt-Svc: h3=":443"; ma=86400
< Age: 293
< Set-Cookie: cf_country-region=RU-VGG; Domain=jetbrains.com; Path=/; Secure
< X-Cache: Hit from cloudfront
< X-Amz-Cf-Pop: HEL50-C1
< X-Amz-Cf-Id: VX8fahkDm5qPZgmns85eBu_5lG4XvdL2NYoo_KLNPLNy34ppOiKy9Q==
<
  0 47748    0     0    0     0      0      0 --:--:--  0:00:01 --:--:--     0HTTP/1.1 301 Moved Permanently
Server: CloudFront
Date: Thu, 26 Oct 2023 11:39:52 GMT
Content-Type: text/html
Content-Length: 167
Connection: keep-alive
Location: https://www.jetbrains.com/
X-Cache: Redirect from cloudfront
Via: 1.1 891326e51cae7827755c7a9147113a54.cloudfront.net (CloudFront)
X-Amz-Cf-Pop: HEL50-C1
Alt-Svc: h3=":443"; ma=86400
X-Amz-Cf-Id: 8DV6_3DOurjX5ZoaJSbrXPn-JMQa739l_mU4d73VtXvpyYnBnf1_Ew==



* Connection #1 to host www.jetbrains.com left intact
```
Запрос для : VSC
*курл*: curl https://code.visualstudio.com -I -v -L -k --User-agent "Google"
```
 processing: https://code.visualstudio.com/
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0*   Trying 13.107.213.44:443...
* Connected to code.visualstudio.com (13.107.213.44) port 443
* schannel: disabled automatic use of client certificate
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0* using HTTP/1.x
> HEAD / HTTP/1.1
> Host: code.visualstudio.com
> User-Agent: Yandex
> Accept: */*
>
< HTTP/1.1 200 OK
< Date: Thu, 26 Oct 2023 11:44:10 GMT
< Content-Type: text/html; charset=utf-8
< Content-Length: 50362
< Connection: keep-alive
< ETag: W/"c4ba-+5KCIEUa9r4T4zqdMWnsq5XA5Nc"
< Strict-Transport-Security: max-age=31536000; includeSubDomains
< Content-Security-Policy: frame-ancestors 'self'
< X-Frame-Options: SAMEORIGIN
< X-XSS-Protection: 1; mode=block
< X-Content-Type-Options: nosniff
< X-Powered-By: ASP.NET
< x-azure-ref: 20231026T114410Z-5cae1fhvfh533fp3w1c65wh1y400000000v000000002ms6z
< X-Cache: CONFIG_NOCACHE
< Accept-Ranges: bytes
<
  0 50362    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0HTTP/1.1 200 OK
Date: Thu, 26 Oct 2023 11:44:10 GMT
Content-Type: text/html; charset=utf-8
Content-Length: 50362
Connection: keep-alive
ETag: W/"c4ba-+5KCIEUa9r4T4zqdMWnsq5XA5Nc"
Strict-Transport-Security: max-age=31536000; includeSubDomains
Content-Security-Policy: frame-ancestors 'self'
X-Frame-Options: SAMEORIGIN
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-Powered-By: ASP.NET
x-azure-ref: 20231026T114410Z-5cae1fhvfh533fp3w1c65wh1y400000000v000000002ms6z
X-Cache: CONFIG_NOCACHE
Accept-Ranges: bytes


* Connection #0 to host code.visualstudio.com left intact
```
