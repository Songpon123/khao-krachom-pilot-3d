# Khao Krachom pilot plots in 3D

Interactive 3D view of the UAV-LiDAR pilot plots P1–P4 at Khao Krachom, Suan Phueng District, Ratchaburi, Thailand (August 2026). Part of a master's thesis at LIESMARS, Wuhan University.

The page shows:

- thinned DJI Zenmuse L1 point clouds of each plot
- four ground models (CSF, PMF, SMRF, DJI Terra) and their differences
- the camera-trap position with 25 m and 50 m buffers (placeholder positions)
- proposed herp survey points and drainage lines derived from the DTM
- ODM orthophotos of P1 and P3, as a flat photo or draped on the canopy surface
- draft species lists for birds, mammals and herps

English and Thai are available from the switch at the top right.

## Data notes

- Species marked **MOCK** are invented for testing the model and are not records.
- Species marked **Recorded** come from Lerdsuchatavanich (2016), Chulalongkorn University.
- No coordinates of sensitive species are stored here. Herp records loaded from a CSV are read in the browser only and are never uploaded.

## Run locally

Serve the folder with any static web server, for example:

```
python3 -m http.server
```

Then open http://localhost:8000. The page loads three.js 0.160.0 from jsDelivr.

---

# แปลงทดลองเขากระโจมแบบ 3 มิติ

หน้าเว็บแสดงแปลงทดลอง UAV-LiDAR P1–P4 ที่เขากระโจม อำเภอสวนผึ้ง จังหวัดราชบุรี (ส.ค. 2569) เป็นส่วนหนึ่งของวิทยานิพนธ์ปริญญาโท LIESMARS มหาวิทยาลัยอู่ฮั่น

รายชื่อชนิดที่ติดป้าย MOCK เป็นข้อมูลสมมติเพื่อทดสอบแบบจำลอง ไม่ใช่ข้อมูลจริง หน้านี้ไม่มีพิกัดของชนิดอ่อนไหว

Songpon Sungngam (ร.อ. ทรงพล สังข์งาม)
