# TPS Group · CEO Dashboard

Dashboard แสดงผล CEO สำหรับ Thai Phasith & TPS Bearing Group

## วิธีอัพเดทข้อมูล

แก้ไขไฟล์ใน folder `data/` แล้ว upload ขึ้น GitHub:

| ไฟล์ | อัพเดทบ่อยแค่ไหน |
|------|-----------------|
| `data/monthly_sales.csv` | ทุกเดือน — เพิ่ม 2 rows (THSITH + TPS) |
| `data/top_products.csv` | ทุกไตรมาส — วางทับทั้งหมด |
| `data/stock.csv` | ทุกครั้งที่รัน stock report — วางทับทั้งหมด |
| `data/at_risk_customers.csv` | ทุกไตรมาส — วางทับทั้งหมด |

## โครงสร้างไฟล์

```
tps-dashboard/
├── index.html        ← Dashboard หลัก
└── data/
    ├── monthly_sales.csv
    ├── top_products.csv
    ├── stock.csv
    └── at_risk_customers.csv
```
