# เริ่มโจทย์เองแท้ๆ 5555 เนี่ยนะ คนที่ขายหนังสือโปรแกรมมิ่ง เปิดคอร์สสอนโค้ดดิ้ง ช่างน่าขันอะไรเยี่ยงนี้

![image](https://user-images.githubusercontent.com/56834844/106225655-3271fb80-6218-11eb-8e24-5fd197e424e5.png)

![image](https://user-images.githubusercontent.com/56834844/106225679-40c01780-6218-11eb-87bc-abfd8feb43af.png)

![image](https://user-images.githubusercontent.com/56834844/106225690-46b5f880-6218-11eb-836e-463f795f11fc.png)

ซึ่งโค้ดนี้ ทั้ง
1. ผิด
2. มั่ว
3. ไม่มีประสิทธิภาพ

## ผิด?
โค้ดนี้จะถูกต้องในกรณีที่ค่า min เป็นสมาชิก 2 ตัวสุดท้ายเท่านั้น

## มั่ว?
สั่งให้ลูป i = 0 แล้วก็ไป if i > 0 ซะอย่างงั้น ทำให้เสียลูปไปฟรีๆ 1 รอบ

## ไม่มีประสิทธิภาพ
มี if ที่ไม่จำเป็นเยอะมาก เช่น if length > 2 เพื่อมาเทียบ 2 ตัวแรกแบบ manual ใน else condition
