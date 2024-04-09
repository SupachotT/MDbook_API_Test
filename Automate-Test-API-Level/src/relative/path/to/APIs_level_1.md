# Automantion Test Postman Level 1
โจทย์ตัวอย่างนี้จะเป็โจทย์การทดสอบการสั่งซื้อสินค้า

เริ่มจากการสร้าง collection ใน postman
และเริ่ม add request ลงใน collection

ใน request แรก เราจะมาเริ่มจาก API Search Product

1. เลือก METHOD ของ request เป็น GET

2. ตั้งค่า URL เป็น http://188.166.247.72/api/v1/product?q=Bicycle&offset=0&limit=20

3. ตั้งค่า Query Params เป็น

| key           |            Value               |
|---------------|--------------------------------|
| q             |           Bicycle              |
| offset        |               0                |
| limit         |               20               |

4. 