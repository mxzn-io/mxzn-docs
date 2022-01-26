# 主面板

*主面板展示当前账户下主要产品设备概览信息*  [原型图](https://www.figma.com/file/eANefR82JBl5YxxYgVqyQu/mxzn?node-id=0%3A1)

- [产品卡片](#产品卡片)
- [设备总数及占比](#设备总数及占比)


#### 产品卡片


#### 设备总数及占比


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
