# wtBRMon
![wtBRMon](https://raw.githubusercontent.com/wtc0der/wtBRMon/master/public_html/screenshot.jpg "wtBRMon")
A OpenWRT realtime per-IP bandwidth Monitor

## Installation
 - Clone Git repository
 - Copy public_html/cgi-bin/wtBRMon in /[Web Root]/cgi-bin/ i.e. /www/cgi-bin/
 - Copy public_html/www in your web server root folder i.e. /www/bandwidth/
 - chmod +x /[Web Root]/cgi-bin/wtBRMon
 - Install luci-app-qos from System/Software

## Launch
 - **Edit /[Web Root]/cgi-bin/wtBRMon and check configuration vars**
 - Open web browser on http://[ROUTER-IP]/cgi-bin/wtBRMon and check if json file is correct (ex: with http://jsonlint.com)
 - Open web browser on http://[ROUTER-IP]/wtBRMon

**Need QOS Uplink and Downlink configured**


Tested on : LinkSys WRT1200AC with OpenWrt Chaos Calmer r46584
