# v2ray-arukas-all-in-one

A v2ray docker image work with nginx for Arukas/IBM/okteto

- v2ray work with websocket
- v2ray request proxy_pass by nginx
- custom v2ray settings
- add environment variables to edit optional setting
  - CLIENT_ID (default ad806487-2d26-4636-98b6-ab85cc8521f7)
  - CLIENT_ALTERID (default 64)
  - CLIENT_WSPATH (default /ws)
  - VER (default 4.28.2)
- don't need custom domain and ssl certificate
- only cost 1 pods

**USE: deploy this image and add default secure route with port 8080 in arukas**

- path to v2ray: https://your.domain/fuckgfw_letscrossgfw
- path to websites: /usr/share/nginx/html/

实例教程参考 ： https://bawodu.com/openshift-v2ray/
