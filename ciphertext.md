# Ciphertext

### ISC
ISC: CISSP Student Glossary ได้ให้ความหมายของ Ciphertext ไว้ว่า Ciphertext คือ รูปแบบที่ถูกเปลี่ยนแปลงของข้อความที่เป็นข้อความปกติ เพื่อให้ไม่สามารถอ่านได้โดยผู้ที่ไม่ได้รับอนุญาต เป็นข้อความที่ถูกแปลงให้เป็นความลับ

![image](https://www.keepersecurity.com/blog/wp-content/uploads/2024/04/Blog-Infographic-1.png)

### SentinelOne
- **👤 SentinelOne:** Ciphertext is the jumbled-up, unreadable string created when you apply encryption to normal, legible data called plaintext. Only an intended recipient with the correct decryption key can convert ciphertext into plaintext. Encrypting plaintext into ciphertext makes the actual information illegible and incomprehensible to unauthorized people or systems.
- **👤 ChatGPT:** Ciphertext คือ สายอักขระที่ไม่สามารถอ่านได้และถูกจัดเรียงใหม่เมื่อมีการใช้การเข้ารหัสข้อมูลที่เป็นข้อความปกติหรือที่เรียกว่า plaintext ข้อความที่เข้ารหัสนี้สามารถแปลงกลับเป็นข้อความปกติได้ก็ต่อเมื่อมีคีย์ในการถอดรหัสที่ถูกต้องเท่านั้น การเข้ารหัสข้อความปกติให้เป็นข้อความที่เข้ารหัสทำให้ไม่สามารถอ่านเดิมให้เข้าใจได้

### ChatGPT
ChatGPT ได้ให้ข้อมูลเกี่ยวกับ Ciphertext ไว้ว่า Ciphertext (ไซเฟอร์เท็กซ์) คือข้อความหรือข้อมูลที่ถูกเข้ารหัส (Encryption) เพื่อป้องกันไม่ให้ผู้ที่ไม่มีสิทธิ์เข้าถึงสามารถอ่านหรือเข้าใจเนื้อหาของข้อความได้ ข้อความที่ยังไม่ถูกเข้ารหัสเรียกว่า Plaintext (เพลนเท็กซ์)

ลักษณะสำคัญของ Ciphertext:
อ่านไม่ออก: Ciphertext จะเป็นรูปแบบข้อความที่ดูไม่มีความหมาย เช่น ตัวเลขหรือตัวอักษรที่สุ่มดูเหมือนไร้ระเบียบ
ความปลอดภัย: การเข้ารหัสทำให้ข้อมูลถูกป้องกันระหว่างการส่งหรือจัดเก็บ
การถอดรหัส: ผู้ที่มี กุญแจถอดรหัส (Decryption Key) และอัลกอริทึมที่เหมาะสมเท่านั้นจึงสามารถแปลง Ciphertext กลับเป็น Plaintext ได้

ตัวอย่าง:
Plaintext: Hello, World!
Ciphertext (หลังเข้ารหัส): E9f0#vM2!x9 (ตัวอย่างเท่านั้น)
Ciphertext เป็นส่วนสำคัญในกระบวนการรักษาความปลอดภัยข้อมูล เช่น ในระบบธนาคาร การสื่อสารออนไลน์ และการจัดเก็บข้อมูลส่วนบุคคล

![image](https://sslinsights.com/wp-content/uploads/2024/07/plaintext-vs-ciphertext-difference.png)

### Gemini
Gemini ได้ให้ข้อมูลเกี่ยวกับ Ciphertext ไว้ว่า Ciphertext หรือ ข้อความเข้ารหัส คือข้อความที่ถูกแปลงจากข้อความธรรมดา (plaintext) ให้เป็นรูปแบบที่อ่านไม่ออก โดยใช้กระบวนการทางคณิตศาสตร์ที่เรียกว่า การเข้ารหัส (encryption) เพื่อปกป้องข้อมูลจากการถูกเข้าถึงโดยบุคคลที่ไม่ได้รับอนุญาต

เปรียบเทียบง่ายๆ:
Plaintext: ข้อความที่เราอ่านเข้าใจได้ เช่น "สวัสดีครับ"
Ciphertext: ข้อความที่ถูกแปลงให้เป็นชุดอักขระหรือตัวเลขที่ไม่มีความหมาย เช่น "hfg8y3t"

ทำไมต้องใช้ Ciphertext?
รักษาความปลอดภัย: ป้องกันไม่ให้บุคคลภายนอกอ่านข้อมูลที่สำคัญ เช่น รหัสผ่าน ข้อมูลส่วนบุคคล หรือข้อมูลทางการเงิน
รักษาความเป็นส่วนตัว: ช่วยให้การสื่อสารเป็นไปอย่างปลอดภัย โดยเฉพาะอย่างยิ่งในการสื่อสารผ่านเครือข่ายสาธารณะ
ป้องกันการดัดแปลงข้อมูล: การเปลี่ยนแปลง ciphertext แม้เพียงเล็กน้อย จะทำให้ข้อมูลที่ถอดรหัสออกมาผิดเพี้ยนไป

### สรุป
จากการสืบค้นข้อมูลเกี่ยวกับ Ciphertext สามารถสรุปได้ว่า Ciphertext คือผลลัพธ์ที่ได้จากการนำข้อความหรือข้อมูลแบบดั้งเดิมที่สามารถอ่านแล้วเข้าใจได้ (Plain Text) มาเข้ารหัสผ่านกระบวนการเข้ารหัส (encryption algorithm) เพื่อให้ไม่สามารถอ่านหรือเข้าใจได้ในรูปแบบเดิม โดยผู้ที่ไม่มี "Key" สำหรับการถอดรหัส (decryption) (ผู้ที่ User หรือ ระบบที่เป็นเจ้าของข้อมูลไม่อนุญาตให้อ่านได้) จะไม่สามารถทำให้ข้อมูลกลับมาเป็น Plain Text ที่เข้าใจได้อีก 

ถ้าต้องการถอดรหัส Ciphertext ให้กลับมาเป็น Plain Text จะต้องใช้ Key ที่ถูกต้องตามกระบวนการถอดรหัส (decryption algorithm) เท่านั้น

![image](https://media.geeksforgeeks.org/wp-content/uploads/20240530193453/1.webp)

### Sample in Daily life
การใช้ QR Code: ข้อมูลที่เข้ารหัสในรูปแบบ QR code เช่น ข้อมูลส่วนตัวหรือข้อมูลธุรกรรม ที่สามารถอ่านได้ด้วยแอปพลิเคชันที่รองรับการถอดรหัส

![image](https://www.researchgate.net/publication/340700567/figure/fig2/AS:881307076796416@1587131389395/a-Encoding-data-in-QR-Codes-b-Encrypting-and-then-encoding-data-in-QR-Codes.ppm)

### Buddy
- [Sathana Mongkol-IN](README)