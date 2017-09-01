## 目录
* [后台管理接口](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#1-后台管理接口)
   * [用户](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#11-用户)
   * [信息管理](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#12-信息管理)
      * [查询设备厂商信息](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#121-查询设备厂商信息)
   * [业务数据查询](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#13-业务数据查询)
      * [查询车辆进出记录](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#131-查询车辆进出记录)
   * [账号管理](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#14-账号管理)
   * [小区信息登录](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#11-小区信息登录)
      * [新增小区](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#111-新增小区)
      * [查询小区信息](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#112-查询小区信息)
      * [更新小区信息](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#113-更新小区信息)
* [后台与APP接口](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#2-后台与app接口)
    * [用户注册与登录](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#21-用户注册与登录)
        * [获取手机验证码](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#211-获取手机验证码)
        * [手机验证码登陆](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#212-手机验证码登陆)
        * [获取用户信息](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#213-获取用户信息)
        * [修改用户信息](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#214-修改用户信息)
        * [用户注销登录](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#215-用户注销登录)
    * [车位查询](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#22-车位查询)
        * [获取周边车位信息](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#221-获取周边车位信息)
        * [获取小区车位信息](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#221-获取小区车位信息)
    * [车位预定](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#23-预定车位)
        * [预定车位(pre-pay)](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#231-预定车位pre-pay)
        * [预定车位(post-pay)](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#232-预定车位post-pay)
        * [获取我的预定](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#233-获取我的预定)
        * [取消车位预定](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#234-取消车位预定)
     * [个人信息查询](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#24-个人信息查询)
        * [查看我的历史停车信息](https://github.com/lynn1982/carshare_srv/blob/master/doc/interfaces.md#241-查看我的历史停车信息)

## 1. 新闻发布系统
### 1.1 内部系统间接口
#### 1.1.1 机器人新闻发布接口