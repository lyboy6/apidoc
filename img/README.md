# pithyAPI 简单 便捷

图床接口

## 图床接口

**请求地址** `http://api.13wl.cn/api/img`

方式 `POST` 类型 `multipart/form-data`

**参数**

|  参数  |  类型  |   描述   |
| :----: | :----: | :------: |
| `file` | `file` | 图片文件 |

**Success 200**

|  参数  |   类型   |     描述     |
| :----: | :------: | :----------: |
| `code` | `Number` |    状态码    |
| `msg`  | `String` |   提示信息   |
| `url`  | `String` | 图片地址信息 |

```js
{
  'code': 200,
  'msg': '上传成功!',
  'data': {
    'url': ''
  },
}
```
