---
title: JMeter
date: 2019-08-09
tags: ["JMeter"]
excerpt: 
---



## オプション
jmeter -n -t /Users/tzuyopon/MyGitHub/jmeter/エディタ画面.jmx -l log.jtl  -e -o report




-H [proxy server hostname or ip address]
-P [proxy server port]
-N [nonproxy hosts] (e.g. *.apache.org|localhost)
-u [username for proxy authentication – if required]
-a [password for proxy authentication – if required]
Example : 
jmeter -H localhost -P 8080 -u username -a password -Nlocalhostt
