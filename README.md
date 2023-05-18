# Face-recognitions
โปรเจคปี 1 เทอม 1 วิชา Fundamental programming 1

จุดประสงค์ : เพื่อสร้างการโปรแกรมในการลดเวลาการเช็คชื่อในห้องเรียนที่มีผู้เรียนจำนวนมาก

ใช้ภาษา python โดยใช้library opencv และ dlib เป็นหลัก โดยมี 2 ไฟล์หลัก คือ featureextrack.py และ Question.py
- featureextrack.py
  ไฟล์ในการนำข้อมูลจากโฟลเดอร์ facedata เพื่อนำมาสร้าง model ในการนำไปใช้คู่กับ GUI
- Question.py 
  ไฟล์ในการรัน interface ให้ผู้ใช้งาน โดยเมื่อกดแสกนใบหน้าหากพบข้อมูลชื่อจะทำการเช็คชื่อและเวลาในฐานข้อมูลที่ใช้ SQL ไฟล์ชื่อ data_stu.db
  แต่หากไม่พบจะแจ้งเตือนว่าไม่พบผู้ใช้ที่ตรงกับใบหน้า

