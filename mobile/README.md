# pithyAPI 简单 便捷

## 手机归属地

**请求地址** `http://api.13wl.cn/api/mobile`

方式 `GET` 类型 `Query String Parameters`

**参数**

|   参数   |   类型   |  描述  |
| :------: | :------: | :----: |
| `mobile` | `String` | 手机号 |

**Success 200**

|   参数    |   类型   |   描述   |
| :-------: | :------: | :------: |
|  `code`   | `Number` |  状态码  |
|   `msg`   | `String` | 提示信息 |
|  `data`   | `Object` | 手机信息 |
| `mobile`  | `String` |  手机号  |
| `address` | `String` |  归属地  |

```js
{
  "code": 200,
  "msg": "获取成功",
  "data": {
      "mobile": "18888888888",
      "address": "北京",
  }
}
```
