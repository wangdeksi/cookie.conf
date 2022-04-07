#寰俊鍏紬鍙�:鎼為浮鐜╁
#鏇存柊鏃堕棿 2022/3/19

hostname = www.babybooks.top,vip.0818km.cn,vni.kwaiying.com,passport.beva.com,gateway.ergedd.com,api.ggmza.cn,api.rr.tv,musicpay.kuwo.cn, vip1.kuwo.cn, audiobookpay.kuwo.cn, tingshu.kuwo.cn, buy.itunes.apple.com, biz.caiyunapp.com, commerce-i18n-api.faceu.mobi,commerce-api.faceu.mobi, pay.wecut.com, zebra.maka.im, vstou.faxingwu.com, account.wps.cn, api.revenuecat.com, iosv2.cjapi.wufan88.com, matrix.fingerplay.cn, api.8897815.com, pan.baidu.com, dashen-api.shuiyinyu.com, api.vuevideo.net, gw.aoscdn.com, api-sub.meitu.com, api2.mubu.com, qianqianapi.chanwind.com



#姹夊牎鍎跨鐫″墠鏁呬簨锛堣В閿佹案涔匳IP锛�
^https:\/\/www\.babybooks\.top\/v0\/profile url script-response-body https://gjds.vip/QX/pojie/sqgs.js


#浜岃泲褰辫锛堣В閿佹案涔匳IP锛�
^http:\/\/vip\.0818km\.cn\/login\/login\/veifys\.html.+ url script-response-body https://gjds.vip/QX/pojie/ed.js


#bigshot锛堣В閿佹案涔匳IP锛�
^https:\/\/vni\.kwaiying\.com\/api\/v1\/user\/profile url script-response-body https://gjds.vip/QX/pojie/bigshot.js

#璐濈摝鍎挎瓕锛堣В閿佹案涔匳IP锛�
^http:\/\/passport\.beva\.com\/passport\/v1\/sdk\/getuserinfo url script-response-body https://gjds.vip/QX/pojie/bweg.js

#鍎挎瓕鐐圭偣锛堣В閿佹案涔匳IP锛�
^http:\/\/gateway\.ergedd\.com\/dduser\/user\/center\/set url script-response-body https://gjds.vip/QX/pojie/egdd.js


#鐟舵睜lsp锛堣В閿佹案涔匳IP锛�
^http:\/\/api\.ggmza.cn\/api\/user\/info url script-response-body https://gjds.vip/QX/pojie/yaochi.js
^http:\/\/api\.ggmza\.cn\/api\/user\/autoLogin url script-response-body https://gjds.vip/QX/pojie/yaochi1.js
^http:\/\/api\.ggmza\.cn\/api\/common\/enterNotice url script-response-body https://gjds.vip/QX/pojie/yaochi2.js


#澶氬瑙嗛 姘镐箙VIP
^https?:\/\/api\.rr\.tv\/.*?Version url reject
https://api.rr.tv/v3plus/index/channel\?pageNum=1&position=CHANNEL_INDEX url script-response-body https://gjds.vip/QX/pojie/ddsp.js
^https?:\/\/api\.rr\.tv\/app\/config\/h5NativeBar url script-response-body https://gjds.vip/QX/pojie/ddsp.js
^https?:\/\/api\.rr\.tv\/v3plus\/index\/channel\?pageNum=1&position=CHANNEL_MY url script-response-body https://gjds.vip/QX/pojie/ddsp.js
^https:\/\/api\.rr\.tv\/user\/privilege\/list url script-response-body https://gjds.vip/QX/pojie/ddsp.js
^https:\/\/api\.rr\.tv\/ad\/getAll url script-response-body https://gjds.vip/QX/pojie/ddsp.js
^https:\/\/api\.rr\.tv\/drama\/app\/get_combined_drama_detail url script-response-body https://gjds.vip/QX/pojie/ddsp.js
https://api.rr.tv/watch/v4 url script-response-body https://gjds.vip/QX/pojie/ddsp.js
https://api.rr.tv/user/profile url script-response-body https://gjds.vip/QX/pojie/ddsp.js

#閰锋垜闊充箰锛堝彲涓嬭浇 姘镐箙VIP 瑙ｉ攣鍚功鐪嬩功VIP锛�
^https?:\/\/audiobookpay\.kuwo\.cn/a\.p url script-response-body https://gjds.vip/QX/pojie/kuwoks.js
^https?:\/\/tingshu\.kuwo\.cn/v2\/api\/user\/ url script-response-body https://gjds.vip/QX/pojie/kuwotingshu.js
^https?:\/\/musicpay\.kuwo\.cn\/music\.pay\?newver=\d url script-request-body https://gjds.vip/QX/pojie/kuwoxz.js
^https?:\/\/vip1\.kuwo\.cn\/(vip\/v2\/user\/vip|vip\/spi/mservice) url script-response-body https://gjds.vip/QX/pojie/kuwohy.js

#瑙嗛鍓緫澶у笀锛堣В閿佹案涔匳IP锛�
^https:\/\/ajj\.fuguizhukj\.cn\/api\/UserProfile\/BasicUserInfo url script-response-body https://gjds.vip/QX/pojie/spjj.js

#Picsew锛堣В閿佷粯璐硅闃咃級
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://gjds.vip/QX/pojie/Picsew.js

#褰╀簯锛堣В閿乂IP锛�
^https:\/\/biz\.caiyunapp\.com\/v2\/user.+ url script-response-body https://gjds.vip/QX/pojie/cytq.js


#杞婚鐩告満 钂告苯娉㈢浉鏈� 锛堣В閿乂IP锛夊叕鐢�
https://(commerce-.*api|pay).(faceu|wecut).(com|mobi)/(commerce|apple)/(iosAppVerifyReceipt.php|v1/subscription/user_info) url script-response-body https://gjds.vip/QX/pojie/qyxj.js

#鏂戦┈娴锋姤锛堟案涔匳IP锛�
^https:\/\/zebra\.maka.im\/api\/user\/info url script-response-body https://gjds.vip/QX/pojie/bmhb.js

#鍗￠€氱浉鏈猴紙VIP锛�
^http:\/\/vstou\.faxingwu\.com\/huihua\/user\/getUser url script-response-body https://gjds.vip/QX/pojie/ktxj.js

#wps
^https?:\/\/account\.wps\.cn\/api\/users url script-response-body https://gjds.vip/QX/pojie/wps.js


#pillow
^https:\/\/api\.revenuecat\.com\/v1\/subscribers.+ url script-response-body https://gjds.vip/QX/pojie/pillow.js


#鎮熼キ
^http:\/\/iosv2\.cjapi\.wufan88\.com\/user\/.+ url script-response-body https://gjds.vip/QX/pojie/wf.js

#鐧藉櫔闊�
^http:\/\/matrix\.fingerplay\.cn\/user\/fetchUserInfo url script-response-body https://gjds.vip/QX/pojie/bzy.js

#椴搁奔瑙嗛锛堣€佸徃鏈猴級
^https:\/\/api\.8897815\.com\/long_video\/advertising url response-body LOGIN_BEFOR response-body 1
^https:\/\/api\.8897815\.com\/long_video\/user\/info url script-response-body https://gjds.vip/QX/pojie/jysp.js

#鐧惧害缃戠洏
https:\/\/pan\.baidu\.com\/rest\/\d\.\d\/membership\/user url script-response-body https://gjds.vip/QX/pojie/bdwp.js

#澶х姘村嵃
^https:\/\/dashen-api\.shuiyinyu\.com\/m\/user\/get_user_info url script-response-body https://gjds.vip/QX/pojie/dssy.js

#VUE 瑙ｉ攣浼氬憳pro
^https:\/\/api\.vuevideo\.net\/api\/v1\/(users\/.+\/profile|subtitle\/prepare) url script-response-body https://gjds.vip/QX/pojie/vue.js

#鍌茶蒋鎶犲浘 vip
^https:\/\/gw\.aoscdn\.com\/base\/vip\/client\/authorizations url script-response-body https://gjds.vip/QX/pojie/aoruankoutu.js

#wink vip
^https:\/\/api-sub\.meitu\.com\/v2\/user\/vip_info\.json.+ url script-response-body https://gjds.vip/QX/pojie/wink.js

#骞曞竷 vip

^https:\/\/api2.mubu.com\/v3\/api\/user/* url script-response-body https://gjds.vip/QX/pojie/mubu.js

#鍗冨崈閰嶉煶VIP
^https:\/\/qianqianapi\.chanwind\.com\/v1\/user/* url script-response-body https://gjds.vip/QX/pojie/qqpy.js 
