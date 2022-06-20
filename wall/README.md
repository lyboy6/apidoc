# pithyAPI 简单 便捷

## 必应每日壁纸

**请求地址** `http://api.13wl.cn/api/wallpaper`

方式 `GET`

**Success 200**

|  参数  |   类型   |       描述       |
| :----: | :------: | :--------------: |
| `code` | `Number` |      状态码      |
| `msg`  | `String` |     提示信息     |
| `url`  | `String` | 必应每日图片地址 |

```js
{
  "code": 200,
  "msg": "获取成功",
  "data": {
      "url": "https://cn.bing.com/th?id=OHR.StrandbadTiefenbrunnen_ZH-CN0240023450_1920x1080.jpg&rf=LaDigue_1920x1080.jpg&pid=hp",
  }
}
```
