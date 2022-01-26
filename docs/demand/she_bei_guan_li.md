# 产品

*展示当前账号下所有产品* [原型图](https://www.figma.com/file/eANefR82JBl5YxxYgVqyQu/mxzn?node-id=2%3A2)

- [产品列表](#产品列表)
  - [产品详情](#产品详情)
  - [功能定义](#功能定义)
- [设备列表](#设备列表)
  - [设备详情](#设备详情)
  - [物模型](#物模型)

**API**
请求示例:

```json
{
  "method": "GET",
  "params": {
    "productName": "name",
    "status": "publish",
    "productType": "1",
    "cate": "1",
    "company": "1"
  }
}
```

返回数据示例

```json
{
  "list": [],
  "current": "number",
  "pageSize": "number",
  "total": "number"
}
```
