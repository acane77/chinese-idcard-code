# 中国各省市县区身份证行政地区编码

## 使用方法
导入 `idcard.sql` 到MySQL数据库即可。

**字段说明**

|字段名|说明|
|---|---|
|code2|前两位编码|
|code4|前4位编码|
|code6|前6位编码|
|province|省份名称|
|province_full_name|省份全称|
|city|地级市|
|district|县级市、区|
|fullname|行政地区全称|
|revoked|行政区是否已被废除|

**视图**

province: 省份表

province_full_name: 省份全称表

city: 地级市表

revoked_city: 已被废除的地级市

---
by Emilia Miyuki

2017/12