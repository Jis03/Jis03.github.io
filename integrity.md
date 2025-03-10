# Integrity

---

### Definition
* refers to the accuracy and consistency of data over its lifecycle. When data has integrity, it means it wasn’t altered during storage, retrieval, or processing without authorization. It’s like making sure a letter gets from point A to point B without any of its content being changed.

* หมายถึง ความถูกต้องและความสอดคล้องของข้อมูลตลอดวงจรชีวิตของมัน เมื่อข้อมูลมีความสมบูรณ์ หมายความว่าข้อมูลไม่ได้ถูกแก้ไขระหว่างการจัดเก็บ การดึงข้อมูล หรือการประมวลผลโดยไม่ได้รับอนุญาต เปรียบเสมือนการทำให้แน่ใจว่าจดหมายเดินทางจากจุด A ไปยังจุด B โดยไม่มีการเปลี่ยนแปลงเนื้อหาใดๆ ระหว่างทาง
  
### Source of definition
* [www.montecarlodata.com](https://www.montecarlodata.com/blog-6-data-quality-dimensions-examples/)
  
---

### Meaning by ChatGPT
* หมายถึง การรับรองว่าข้อมูลมีความถูกต้อง สมบูรณ์ และสอดคล้องกันในทุกขั้นตอนของการจัดการข้อมูล ตั้งแต่การสร้าง จัดเก็บ ไปจนถึงการใช้งาน โดยมีเป้าหมายเพื่อให้ข้อมูลสามารถนำไปใช้ได้อย่างน่าเชื่อถือและมีประสิทธิภาพสูงสุด

---

### Meaning by Gemini
* หมายถึง ความสมบูรณ์และความถูกต้องของข้อมูล นั่นคือ ข้อมูลที่เรามีอยู่นั้นต้องครบถ้วนสมบูรณ์ ไม่ขาดหายไปส่วนใดส่วนหนึ่ง และต้องเป็นข้อมูลที่ถูกต้องตามความเป็นจริง ไม่มีการบิดเบือนหรือปลอมแปลง
  
---

### My Summary
* หมายถึง ข้อมูลที่มีความถูกต้องสมบรูณ์ และไม่มีการบิดเบือนใด ๆ มีความน่าเชื่อถือเพื่อนำไปใช้งานต่อ
  
---

### Sample
#### 1.การป้องกันข้อมูลไม่ให้ขาดหาย
* ข้อมูลที่จำเป็นต้องกรอกให้ครบถ้วน
* ตัวอย่าง:
เมื่อเพิ่มลูกค้าใหม่ในระบบ ชื่อ-นามสกุล และ หมายเลขโทรศัพท์ ต้องเป็นฟิลด์ที่บังคับกรอก (Required Fields) เพื่อป้องกันข้อมูลไม่ครบ ชื่อ: นายวิชัย โทรศัพท์: 0812345678 หากไม่กรอกหมายเลขโทรศัพท์ ระบบจะแจ้งเตือนว่า "ข้อมูลไม่ครบ"

#### 2.การป้องกันการบิดเบือนข้อมูล
* ป้องกันไม่ให้ข้อมูลถูกแก้ไขโดยไม่ได้รับอนุญาต
* ตัวอย่าง:
ในระบบบัญชี การแก้ไขข้อมูลการทำธุรกรรมควรต้องมีการยืนยันตัวตนและบันทึกว่าใครเป็นผู้แก้ไข (Audit Trail) การปรับยอดบัญชี ต้องมีบันทึกว่า ผู้แก้ไข: Admin วันที่: 29 ธันวาคม 2024 รายละเอียดการเปลี่ยนแปลง: เพิ่มยอด 10,000 บาท

---

