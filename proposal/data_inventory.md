**Data inventory**

| Dataset                    | Source                | ใช้ตอบ | ข้อจำกัดที่รู้แล้ว              |
| -------------------------- | --------------------- | ------ | --------------------- |
| Sentinel-2 SR HARMONIZED              | European Space Agency |  Surface Reflectance   | - |
| Chlorophyll-a / Secchi / TSI | คำนวณจาก Sentinel-2 SR HARMONIZED               | คุณภาพน้ำ      | บางจุดใน ROI ไม่มีข้อมูล           |
| ตำแหน่งท่าเรือ             | open source data (OSM) | จุดออกเรือ     | -
| เส้นทางเดินเรือ              | open source data (OpenSeaMap)  | พื้นที่ที่ต้องเลี่ยง     | ต้อง digitize เอง        |
| ตำแหน่งแท่นขุดเจาะน้ำมัน              | open source data (Global Energy Monitor) | พื้นที่ที่ต้องเลี่ยง     | -        |
| ROI                        | shapefile             | ขอบเขตพื้นที่ศึกษา    | -              |


**การดึงตำแหน่งท่าเรือจา่ก OSM**

<img width="718" height="373" alt="Screenshot 2026-04-02 205705" src="https://github.com/user-attachments/assets/931a6f7e-b8d0-4241-9757-0bd1a66b3099" />



