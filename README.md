# NotificationSync
通过 FCM 将你的通知从一个安卓设备转发到另一个安卓设备

你可以使用带有谷歌服务的旧小米、OPPO、Vivo 或魅族设备作为服务器，
将 mipush、OPPO push、Vivo push 或魅族推送的通知转发到你的主要日常设备，如三星 Galaxy、Google Pixel、Sony Xperia 等。
由于大多数中国安卓应用不支持谷歌 FCM 推送，而除了小米、OPPO、Vivo 和魅族之外的设备只能使用谷歌 FCM 接收后台通知（GFW太恶心了）
你的主要设备不需要 root，服务器也不需要，你只需要确保服务器有稳定的国际互联网连接。
然后你的主要设备就可以接收 FCM 推送。

此外，三星中国已经与个推和极光推送合作，提供统一的推送服务，但只有少数中国应用使用它来推送广告，而不是重要信息。

# 使用方式
git clone https://github.com/Ayndpa/NotificationSync.git # 下载到本地

使用 Android Studio 等 IDE 打开

修改google-services.json和代码中的notificationpush-67db1-firebase-adminsdk-2sikf-401fd6e984.json为自己的firebase

编译 运行
