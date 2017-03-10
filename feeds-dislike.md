# /feeds/dislike 接口
---

#### 说明
feed流里不喜欢某内容接口

#### 请求
```
POST /feeds/dislike/<type:\w+>/<content_id:\d+> HTTP/1.1
```

#### 参数：
```
|参数|类型|是否必需|说明|示例|
|type|string|Y| 内容类型 | "user" or "recording" |
|content_id|int|Y|内容ID|user_id or recording_id |
```

#### 响应
```
HTTP/1.1 200 OK
```

