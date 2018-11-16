# 登录相关  
## 相关包和类  
### "com.cmb.plugin.signin"  
#### SignInApplication  
    一些初始化相关配置
#### "com.cmb.plugin.signin.data"  
    1. "com.cmb.plugin.signin.data.remote"--网络请求
      * ProfileService、SignInService--登录相关接口  
    2. "com.cmb.plugin.signin.data.model"--登录请求相关数据类型  
    3. "com.cmb.plugin.signin.injection"--底层相关基类  
#### "com.cmb.plugin.signin.ui"  
    1. "com.cmb.plugin.signin.ui.base"-- Activity,fragment相关基类  
    2. "com.cmb.plugin.signin.ui.biology"--生物登录、设置相关
      * BiometricLoginActivity--生物登录界面（指纹、手势）
      * BiometricSettingActivity--生物设置界面（指纹、手势）
      * FingerprintLoginFragment--指纹登录
      * FingerprintSettingFragment--指纹设置
      * PatternLockLoginFragment--手势登录
      * PatternLockSettingFragment--手势设置
    3. "com.cmb.plugin.signin.ui.main"--登录跳转入口相关
      * AccountProfileActivity--账户信息
      * MoreLoginOptionsFragment--更多登录方式
    4. "com.cmb.plugin.signin.ui.sms"
      * SmsVerificationActivity--短信验证相关
#### "com.cmb.plugin.signin.verify"  
    1. VerifyActivity，VerifyFragment--登录二次验证相关界面
     
     
     
     
