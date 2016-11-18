#ใบงานที่ 12
##การเขียนโปรแกรมกราฟฟิกส์ด้วย GDI+ (3)
##กล่าวนำ
ใบงานนี้ มีวัตถุประสงค์ เพื่อให้นักศึกษา ได้รู้จักกับ GDI+ ซึ่งจะช่วยให้นักษาสามารถ
* โหลดภาพชนิดต่างๆ เพื่อมาแสดงบนฟอร์มได้
* จัดการกับภาพโดยวิธีการง่ายๆ เช่น พลิกภาพ หมุนภาพ และเขียนข้อความลงบนภาพได้

###การโหลดภาพเพื่อแสดงบน Form
Project นี้จะโหลดภาพจากไฟล์ (ชนิดใดก็ได้) มาแสดงผลบน Form 
* สร้าง Project ใหม่เป็น Visual C#
* แก้ไข code เพื่อโหลดและแสดงภาพบน Form 
</p align = "center">
<img src="https://github.com/Desktop-Programming-Lab-2559/LAB-12/blob/master/imgs/lab12-1.png">
</p> 

**หมายเหตุ** ในบรรทัดที่ 23 หากนักศึกษาต้องการแสดงไฟล์อื่น ก็ให้ใส่ path พร้อมชื่อ แต่ต้องใส่ \\ แทน \ เนื่องจาก ในภาษา C# นั้น เครื่องหมาย \ จะเป็น escape character เช่นเดียวกับภาษา c และ c++

![](https://github.com/Tooktasupaporn/LAB-12/blob/master/imgs/lab12-0.PNG?raw=true)
##การ Zoom ภาพ
การ Zoom ภาพ คือการกำหนดให้ขนาดของพื้นที่แสดงผลต่างไปจากขนาดที่แท้จริงของภาพ (Zoom in, Zoom out) นอกจากนี้เรายังสามารถเลือกส่วนของภาพที่จะแสดงได้อีกด้วย

### การ Zoom out  
คือการกำหนดให้ Rectangle ปลายทาง เล็กกว่าขนาดจริงของภาพ
 </p align = "center">
<img src="https://github.com/Desktop-Programming-Lab-2559/LAB-12/blob/master/imgs/lab12-2.png">
</p> 


### การ Zoom in  
คือการกำหนดให้ Rectangle ปลายทาง โตกว่า Rectangle ของภาพ ในที่นี้จะเลือกภาพมาแสดง
 
</p align = "center">
<img src="https://github.com/Desktop-Programming-Lab-2559/LAB-12/blob/master/imgs/lab12-3.png">
</p> 
![](https://github.com/Tooktasupaporn/LAB-12/blob/master/imgs/lab12-1.PNG?raw=true)

### การพลิกและหมุนภาพ
 </p align = "center">
<img src="https://github.com/Desktop-Programming-Lab-2559/LAB-12/blob/master/imgs/lab12-4.png">
</p> 
![](3.	https://github.com/Tooktasupaporn/LAB-12/blob/master/imgs/lab12-%E0%B8%81%E0%B9%88%E0%B8%AD%E0%B8%99%E0%B8%97%E0%B9%89%E0%B8%B2%E0%B8%A2.PNG?raw=true)

## การเขียนข้อความลงในภาพ
 </p align = "center">
<img src="https://github.com/Desktop-Programming-Lab-2559/LAB-12/blob/master/imgs/lab12-5.png">
</p> 
![](https://github.com/Tooktasupaporn/LAB-12/blob/master/imgs/lab12-2.PNG?raw=true)

##แบบฝึกหัด
ให้วาดตัวการ์ตูน Doraemon โดยใช้คำสั่งต่างๆ ทางด้านกราฟฟิกส์ พร้อมทั้งใส่ชื่อ นามสกุล และรหัสนักศึกษาของตนเองลงไปด้วย (ห้ามใช้วิธีการใส่รูปภาพ)

![](https://github.com/Tooktasupaporn/LAB-12/blob/master/imgs/domon%20final2.PNG?raw=true)

**[ตัวอย่างงานวาดภาพ Doraemon ของรุ่นพี่](https://github.com/Desktop-Programming-Lab-2559/LAB-12/blob/master/Doraemon.md)**
