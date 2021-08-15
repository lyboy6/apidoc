# pithyAPI 简单 便捷

## qq 名称头像

**请求地址** `http://api.13wl.cn/api/qq.php`

方式 `GET` 类型 `Query String Parameters`

**参数**

|  参数  |   类型   |                  描述                   |
| :----: | :------: | :-------------------------------------: |
|  `qq`  | `String` |                  qq 号                  |
| `size` | `String` | 头像的大小 默认 100 可选值 100 或者 640 |

**Success 200**

|   参数   |   类型   |    描述     |
| :------: | :------: | :---------: |
|  `code`  | `Number` |   状态码    |
|  `msg`   | `String` |  提示信息   |
|  `data`  | `Object` |   QQ 信息   |
|   `qq`   | `String` |    QQ 号    |
|  `name`  | `String` |   QQ 名称   |
| `avatar` | `String` | QQ 头像地址 |

```js
{
  "code": 200,
  "msg": "获取成功",
  "data": {
      "qq": "706344353",
      "name": "你别出现在我凌晨的梦里",
      "avatar": "https://q1.qlogo.cn/g?b=qq&nk=706344353&s=640"
  }
}
```
