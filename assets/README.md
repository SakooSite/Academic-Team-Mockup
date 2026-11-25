# assets

สคริปต์ของหน้ารายงานในโฟลเดอร์ `reports/` 5 หน้า กับไลบรารีที่หน้ารายงานใช้ ไฟล์ทั้งหมดอยู่ใน `academic-report/`

| ไฟล์ | หน้าที่ |
|---|---|
| `js/core/report-data.js` | สร้างข้อมูลจำลองชุดเดียวที่รายงานทั้ง 5 หน้าใช้ร่วมกัน ห้องเรียน รายวิชา ครู และรายชื่อนักเรียนอ่านจาก `grading/assets/js/data.js` จึงตรงกับหน้าบันทึกคะแนน ส่วนคะแนนและการเข้าเรียนสร้างขึ้นสำหรับรายงานโดยเฉพาะ |
| `js/core/report-preview.js` | หน้าต่างแสดงตัวอย่างก่อนส่งออกหรือพิมพ์รายงาน |
| `js/scope-chip.js` | แสดงช่วงข้อมูลของรายงาน เช่น ภาคการเรียนปัจจุบัน ไว้ที่ header ด้านบน |
| `js/modules/attendance-report.js` | สคริปต์ของหน้า `reports/attendance-report.html` |
| `js/modules/unable-exam-report.js` | สคริปต์ของหน้า `reports/unable-exam-report.html` |
| `js/modules/score-per-subject.js` | สคริปต์ของหน้า `reports/score-subject-report.html` |
| `js/modules/average-score-year.js` | สคริปต์ของหน้า `reports/average-score-year-report.html` |
| `js/modules/record-report.js` | สคริปต์ของหน้า `reports/record-report.html` |
| `vendor/chart.umd.min.js` | ไลบรารี Chart.js สำหรับวาดกราฟ |

หน้ารายงานอื่นใน `reports/` เขียนสคริปต์ไว้ในไฟล์ HTML ของหน้านั้นเอง
