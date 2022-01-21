## 页面列表

- [x] 1产品列表
    - [x] 1.1列表
    - [x] 1.2产品详情
        - [x] 1.2.1产品信息
        - [x] 1.2.2物模型
        - [x] 1.2.3告警设置
- [x] 2设备列表
    - [x] 2.1列表
    - [x] 2.2设备详情
        - [x] 2.2.1设备信息
        - [x] 2.2.2物模型
        - [x] 2.2.3日志
- [ ] 3规则引擎
- [ ] 4日志管理
- [x] 5大屏管理

#### 1产品列表

##### 1.1列表
**列表展示当前账号下所有产品，使用表格方式呈现。**  

**过滤器**: 名称, 发布状态，产品类型, 所属品类  
**表格显示字段**: 名称, productId, productKey, 发布状态, 所属品类， 所属机构  
**操作**: 编辑, 删除  

**示意图:**  [FIGMA 原型](https://www.figma.com/file/cCABX9I9LsFxvgMm4Bgyd2/mxzn-io?node-id=0%3A1)

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
