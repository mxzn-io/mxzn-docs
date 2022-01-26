# 主面板

*主面板展示当前账户下主要产品设备概览信息*  [原型图](https://www.figma.com/file/eANefR82JBl5YxxYgVqyQu/mxzn?node-id=0%3A1)

- [产品卡片](#产品卡片)
- [设备总数及占比](#设备总数及占比)


#### 产品卡片

![logo](images/card.png ':size=1188x160')

>产品卡片展示了主要产品的设备状态信息，如智能水渠，农机终端等，client账户若无此产品则卡片状态信息如在线离线设备等默认为0

**接口信息**

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

```json
{
  "list": [],
  "current": "number",
  "pageSize": "number",
  "total": "number"
}
```

#### 设备总数及占比


**API**

