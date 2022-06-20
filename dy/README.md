# pithyAPI 简单 便捷

## 解析抖音地址

**请求地址** `http://api.13wl.cn/api/dy`

方式 `GET` 类型 `Query String Parameters`

**参数**

| 参数  |   类型   |    描述    |
| :---: | :------: | :--------: |
| `url` | `String` | 抖音短链接 |

**Success 200**

|      参数      |   类型   |     描述     |
| :------------: | :------: | :----------: |
|     `code`     | `Number` |    状态码    |
|     `msg`      | `String` |   提示信息   |
| `origin_cover` | `Array`  |     封面     |
|     `play`     | `String` | 抖音解析地址 |
|    `title`     | `String` |   抖音标题   |

```js
{
  "code": 200,
  "msg": "获取成功",
  "data": {
      "origin_cover": [],
      "play": "https://aweme.snssdk.com/aweme/v1/play/?video_id=v0200fg10000c7a1l1rc77u0ipguon3g&ratio=720p&line=0",
      "title": "我不过一介庶民，怎敌姑娘名满京城？#国漫 "
  }
}
```
