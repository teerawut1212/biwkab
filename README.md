﻿# biwkab project

# คำสั่งพื้นฐาน
## คำสั่ง CLI(command line interface)
ก่อนจะไปใช้คำสั่ง git คำสั่ง CLI ก็เป็นสิ่งที่ต้องรู้ด้วย ไม่งั้นเราจะไปต่อกันไม่ได้ ถ้าใครรู้แล้วก็ข้ามไปคำสั่ง git ได้เลย คำสั่งที่ต้องรู้คือ

* pwd (print working directory (dir)) ใช้เมื่ออยากรู้ว่าตอนนี้เราอยู่ที่ dir ไหน
* cd (change dir) เพื่อเปลี่ยนไปยัง dir อื่น
* ls (list) ดูว่าใน dir ที่เราอยู่มีไฟล์หรือโฟลเดอร์อะไรบ้าง
* mkdir (make dir) สร้างโฟลเดอร์ใหม่ขึ้นมา
* touch สร้างไฟล์ใหม่

## คำส่ัง git
โดยพื้นฐานแล้ว git มีคำสั่งที่หลากหลายมากมายมหาศาลมาก แต่เราจะเริ่มกันด้วยคำสั่งเบื้องต้นที่ทำให้เราสามารถใช้งานได้ก่อนอันได้แก่

* git init ใช้สร้าง local repo ขึ้นมา 
* git add ใช้ stage เพื่อติดตามตามความเปลี่ยนแปลงของไฟล์
* git commit ใช้เพื่อบันทึกความเปลี่ยนแปลงที่เกิดขึ้นสู่ local repo
* git push ใช้เพื่อส่ง commit ไปยัง remote repo
* git clone ใช้เพื่อคัดลอก repo จาก remote มายัง local
* git fetch ใช้ดึงความเปลี่ยนแปลงจาก remote มายัง local แต่ยังไม่รวมเข้าด้วยกัน
* git merge ใช้รวมความเปลี่ยนแปลงที่ได้มาจาก fetch เข้ากับ local
* git pull ใช้ดึงความเปลี่ยนแปลงจาก remote มายัง local และรวมเข้าด้วยกัน (มีค่าเท่ากับ fetch+merge)
* git log ใช้เพื่อดูว่า git repo มี commit อะไรแล้วบ้าง
 
## My bar 
[Link Ref.](https://tupleblog.github.io/use-git-part1/)
