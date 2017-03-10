# /recordings/favorite 接口
---

#### 说明
收藏作品接口

#### 请求
```
POST    /recordings/<recording_id:\d+>/favorite HTTP/1.1  添加收藏
DELETE  /recordings/<recording_id:\d+>/favorite HTTP/1.1  删除收藏
```

#### 是否需要登录
```
是
```

#### 参数：
```
|参数|类型|是否必需|说明|示例|
|recording_id|int|Y|作品ID| -- |
```

#### 响应
```
HTTP/1.1 200 OK
```

