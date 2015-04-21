WiAuth
=====

概述
-----
在日常生活中，互联网用户需要面对大量授权登录场景，已有的方式大多需要用户交互验证或者额外的硬件。眼下，国家网络实名制进程正在逐步推进，找到一种廉价而有效的方式迫在眉睫。因此，我们提出了一种既快速又安全，同时可以解决实名制的身份认证算法。本算法依靠局域网通信，以手机作为硬件令牌，使用token传递机制，使用户只需点击按钮即可完成授权操作。此外，其利用滚动密钥机制和DES加密算法，及配对口令体系，保障了较高的安全性。同时利用手机号开户时录入的实名信息，通过SIM卡ICCID查询，实现实名验证和登录保护。本算法实现了较好的用户体验、安全保障以及实名制解决方案。当下，智能手机与家庭局域网络已经十分普及，此算法的推广容易被用户接受。同时，算法提供了API接口以及SDK，为第三方软件使用此算法提供了可行的方案，具有较好的普适性和可移植性。本算法可应用在网络登陆、实名安全支付和网吧实名登记等场景中。

作者
-----

- @coderfox(Yuze Fu,傅禹泽)<coderfox.fu@gmail.com>
- @hackerchai(Yisheng Chai,柴轶晟)<admin@hackerchai.com>
- @LeeChenyu(Chenyu Li,李晨宇)

子项目
-----

- [WiAuth-Windows](https://github.com/WiAuth/WiAuth-Windows) 接口层在Windows上的实现
- [WiAuth-Android](https://github.com/WiAuth/WiAuth-Android) 鉴权层在Android上的实现
- [WiAuth-Front](https://github.com/WiAuth/WiAuth-Front) 前端
- [WiAuth-Demo](https://github.com/WiAuth/WiAuth-Demo) 演示应用
- [WiAuth-Backend](https://github.com/WiAuth/WiAuth-Backend) 服务器端
- [WiAuth-SDK](https://github.com/WiAuth/WiAuth-SDK) SDK
