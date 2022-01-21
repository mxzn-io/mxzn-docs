## 页面列表

- [x] 1主面板
    - [x] [主面板](#主面板)
- [x] 产品
    - [x] [产品列表](#产品列表)
    - [x] [产品详情](#产品详情)
        - [x] [产品信息](#产品信息)
        - [x] [物模型](#物模型)
        - [x] [告警设置](#告警设置)
- [x] 设备列表
    - [x] [设备列表](#)
    - [x] [设备详情](#)
        - [x] [设备信息](#)
        - [x] [物模型](#)
        - [x] [日志](#)
- [ ] 3规则引擎
- [ ] 4日志管理
- [x] 5大屏管理

#### 主面板
**主面板通过图表的方式呈现常用指标**

**原型图**  [主面板](https://www.figma.com/file/eANefR82JBl5YxxYgVqyQu/mxzn?node-id=0%3A1)

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

#### 产品

##### 产品列表

**列表展示当前账号下所有产品，使用表格方式呈现。**  

**过滤器**: 名称, 发布状态，产品类型, 所属品类  
**表格显示字段**: 名称, productId, productKey, 发布状态, 所属品类， 所属机构  
**操作**: 编辑, 删除  

**原型图:**  [列表](https://www.figma.com/file/eANefR82JBl5YxxYgVqyQu/mxzn?node-id=2%3A2)

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

#### 产品详情

**详情页展示当前产品详情数据**  

**原型图:**  