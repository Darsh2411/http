
#### 工具openssl
```
open as admin, 

openssl pkcs12 -in client-gm-moba-youngjoygame-com-with-password.pfx  -nocerts -out privatekey.pem
```
[视频](https://www.youtube.com/watch?v=P-DeGwrL0K4),
[nodejs-ssl-unable-to-get-local-issuer-certificate](https://stackoverflow.com/questions/43227809/nodejs-ssl-unable-to-get-local-issuer-certificate),
[what-is-the-difference-between-pem-csr-key-and-crt](https://crypto.stackexchange.com/questions/43697/what-is-the-difference-between-pem-csr-key-and-crt)


#### 证书扩展名.pfx, .crt
[https://whatis.techtarget.com/fileformat/CRT-Certificate-file](https://whatis.techtarget.com/fileformat/CRT-Certificate-file),

[Difference between .pfx and .cert certificates](https://security.stackexchange.com/questions/29425/),

[convert-pfx-to-cer](https://stackoverflow.com/questions/403174/convert-pfx-to-cer),
[how-to-get-pem-file-from-key-and-crt-files](https://stackoverflow.com/questions/991758/how-to-get-pem-file-from-key-and-crt-files),
[https://knowledge.digicert.com/solution/SO21807.html](https://knowledge.digicert.com/solution/SO21807.html),
[pem-ssl-creation](https://www.digicert.com/ssl-support/pem-ssl-creation.htm),
[what-is-a-pem-file-and-how-does-it-differ-from-other-openssl-generated-key-file](https://serverfault.com/questions/9708/what-is-a-pem-file-and-how-does-it-differ-from-other-openssl-generated-key-file),

### http authentication, ssl, http, Cross origin requests:
[cross-origin-requests-are-only-supported-for-protocol-schemes-error-in-react](https://stackoverflow.com/questions/49983665/cross-origin-requests-are-only-supported-for-protocol-schemes-error-in-react)
,
[has-been-blocked-by-cors-policy-axios-post](https://forum.vuejs.org/t/has-been-blocked-by-cors-policy-axios-post/50428)
,
[vue-and-axios-cors-error-no-access-control-allow-origin-header-is-present-on-t](https://stackoverflow.com/questions/41778860/vue-and-axios-cors-error-no-access-control-allow-origin-header-is-present-on-t)
,
[web-http-cors](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS)
,
[enable-cors-server_expressjs](https://enable-cors.org/server_expressjs.html)
,
[how-to-allow-cors](https://stackoverflow.com/questions/7067966/how-to-allow-cors/38500226#38500226)



#### server requires username and password
Microsoft NTLM Authentication
[server-http-localhost8080-requires-a-user-name-and-a-password-the-server-says](https://stackoverflow.com/questions/32960741/server-http-localhost8080-requires-a-user-name-and-a-password-the-server-says)

#### Error: unable to get local issuer certificate
[https://github.com/nodejs/node/issues/3742](https://github.com/nodejs/node/issues/3742)