
Curl ile HTTP Request Headerli Mederli
--------------------------------------

    curl -v -k -H "Content-Type: application/json" -H "X-NITRO-USER:nsroot" -H "X-NITRO-PASS:nsroot" -X POST -d '{"server":{"name":"server1","IPAddress":"8.8.8.8"}}' https://10.111.34.220/nitro/v1/config/server

Status Code ve benzeri response lari test etmek isteyenlere

    http://httpbin.org

HTTP Error Codes

    http://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html

Netscaller API Link

    http://docs.citrix.com/en-us/netscaler/11/nitro-api/nitro-rest.html

    Ek olarak http://www.citrix.com/downloads/netscaler-adc/sdks.html direk SDK indirin
