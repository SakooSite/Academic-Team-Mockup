# reports

โมดูลรายงานวิชาการ มี 16 หน้า หน้าที่อยู่ในเมนูเป็นหน้ารายงานหลัก ส่วนหน้ารายละเอียดเปิดจากการกดแถวหรือปุ่มในหน้ารายงานหลัก

## หน้ารายงานหลัก

| หน้า | ชื่อในเมนู | เนื้อหา |
|---|---|---|
| `overview.html` | ภาพรวม | สถานะงานหลักของปีการศึกษา และห้องหรือรายวิชาที่ผิดปกติมากที่สุด เป็นหน้าแรกของระบบ |
| `student-retake-management.html` | รายงานผลการสอบซ่อม | สรุปนักเรียนและรายวิชาที่ต้องสอบซ่อม |
| `student-score-ranking.html` | รายงานจัดอันดับคะแนนรายวิชา | จัดอันดับคะแนนนักเรียนในแต่ละรายวิชา |
| `subject-results.html` | รายงานสรุปผลการเรียนรู้ | สรุปผลการเรียนของแต่ละรายวิชา |
| `attendance-report.html` | รายงานการเข้าเรียน | การเข้าเรียนของนักเรียน สำหรับ admin |
| `teacher-attendance.html` | รายงานการเข้าเรียน | การเข้าเรียนเฉพาะรายวิชาที่ครูคนนั้นสอน สำหรับครู |
| `unable-exam-report.html` | รายงานผู้ไม่มีสิทธิ์สอบ | นักเรียนที่เวลาเรียนไม่ถึงเกณฑ์ |
| `score-subject-report.html` | รายงานคะแนนรายวิชา | คะแนนของนักเรียนในแต่ละรายวิชา |
| `average-score-year-report.html` | รายงานคะแนนเฉลี่ยรายปี | คะแนนเฉลี่ยเทียบรายปีการศึกษา |
| `record-report.html` | รายงานระเบียนสะสม / GPAX | ผลการเรียนสะสมและเกรดเฉลี่ยสะสมของนักเรียน |

## หน้ารายละเอียด

| หน้า | เปิดจาก | เนื้อหา |
|---|---|---|
| `fail-student-detail.html` | `overview.html` | รายชื่อนักเรียนที่ต้องปรับปรุง |
| `subject-retake-detail.html` | `student-retake-management.html` | รายละเอียดรายวิชาที่มีนักเรียนสอบซ่อม |
| `student-retake-detail.html` | `student-retake-management.html` | รายละเอียดการสอบซ่อมของนักเรียนรายคน |
| `student-list-by-classroom.html` | ยังไม่มีลิงก์จากหน้าอื่น เปิดด้วย URL โดยตรง | รายชื่อนักเรียนสอบซ่อมแยกตามห้อง |
| `student-score-ranking-detail.html` | `student-score-ranking.html` | รายละเอียดการจัดอันดับของรายวิชาที่เลือก |
| `student-results-detail.html` | `subject-results.html` | ผลการเรียนรายวิชาแยกรายนักเรียน |

หน้า `attendance-report`, `unable-exam-report`, `score-subject-report`, `average-score-year-report` และ `record-report` ใช้สคริปต์จากโฟลเดอร์ `assets/` หน้าอื่นเขียนสคริปต์ไว้ในไฟล์ HTML ของตัวเอง
