"# Homework"

Create branch
git branch // ดู branch

git checkout -b {branch name} // สร้างและสลับ branch

git branch // ดูตำแหน่ง branch ตอนนี้

echo "your message" >> dev.md

git commit -m "your message"

git push origin {branch name} // อัพ branch ขึ้น server

up branch ขึ้น server เสร็จเรียบร้อย ... ตรวจสอบใน github

Other branch command
$ git merge {branch name} // รวม bracnh กับ master *(ทำใน master)

$ git checkout {branch name} {file name} // ย้ายไฟล์จาก branch ต้นทาง **(สลับมาอยู่ใน branch ปลายทางก่อน)

$ git branch -d {branch name} // ลบ branch

$ git merge --no-ff {branch name} // รวมไฟล์จาก branch
