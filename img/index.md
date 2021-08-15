# pithyAPI 简单 便捷

目前完成的

百度图床接口

预览地址: http://api.13wl.cn/image

## 百度图床接口

**请求地址** `http://api.13wl.cn/api/img.php`

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
| `data` | `Object` | 图片地址信息 |

```js
{
  'code': 200,
  'msg': '上传成功!',
  'data': {
    'url': ''
  },
}
```
