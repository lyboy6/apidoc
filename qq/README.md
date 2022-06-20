# pithyAPI 简单 便捷

## qq 名称头像

**请求地址** `http://api.13wl.cn/api/qq`

方式 `GET` 类型 `Query String Parameters`

**参数**

| 参数 |   类型   | 描述  |
| :--: | :------: | :---: |
| `qq` | `String` | qq 号 |

**Success 200**

|  参数  |   类型   |    描述     |
| :----: | :------: | :---------: |
| `code` | `Number` |   状态码    |
| `msg`  | `String` |  提示信息   |
| `name` | `String` |   QQ 名称   |
| `pic1` | `String` | QQ 头像地址 |
| `pic2` | `String` | QQ 头像地址 |

```js
{
  "code": 200,
  "msg": "获取成功",
  "data": {
      "name": " QQ名称",
      "pic1": "http://qlogo2.store.qq.com/qzone/706344353/706344353/100",
      "pic1": "http://qlogo2.store.qq.com/qzone/706344353/706344353/640"
  }
}
```
