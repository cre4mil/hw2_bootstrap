# hw2_bootstrap

# git command used in this lab
- git clone https://github.com/cre4mil/hw2_bootstrap.git
- md images
- git add .
- git commit -m "โครงสร้างเริ่มต้น"
- git add images
- git commit -m "เพิ่มไฟล์รูปภาพ"

- git checkout -b feature/home-page
- git add home.html
- git commit -m "เพิ่มเค้าโครง html ของ home"
- git add home.html
- git commit -m "เพิ่ม link bootstrap 5"
- git add home.html
- git commit -m "ใส่ menu,logo,search"
- git add home.html
- git commit -m "เพิ่มรูป logo"
- git add home.html
- git commit -m "เพิ่ม section"
- git add home.html
- git commit -m "เพิ่มส่วนของ highlight"
- git add home.html
- git commit -m "เพิ่ม Carousel"
- git add home.html
- git commit -m "เพิ่ม style"
- git add home.html
- git commit -m "เพิ่ม footer"
- git add home.html
- git commit -m "แก้ไขรูปภาพ"
- git add home.html
- git commit -m "แก้ไข link และ navbar"
- git add home.html
- git commit -m "แก้ไข footer"

- git checkout development
- git checkout -b feature/about-page
- git add about.html
- git commit -m "เพิ่ม nav และ link bootstrap"
- git add about.html
- git commit -m "เพิ่มส่วนแนะนำสถานที่เที่ยว"
- git add about.html
- git commit -m "เพิ่ม footer"
- git add about.html
- git commit -m "แก้ไข link และ navbar"
- git add about.html
- git commit -m "แก้ไข footer"

- git checkout development
- git checkout -b feature/contact-page
- git add contact.html
- git commit -m "เพิ่มเค้าโครง html ของ contact"
- git add contact.html
- git commit -m "เพิ่ม link เชื่อมกับ Bootstrap และ Font"
- git add contact.html
- git commit -m "ใส่ menu,logo,search"
- git add contact.html
- git commit -m "เพิ่ม main content"
- git add contact.html
- git commit -m "เพิ่มปุ่ม และสร้าง Modal สำหรับฟอร์มติดต่อ"
- git add contact.html
- git commit -m "เพิ่ม footer"

- git checkout development
- git merge feature/home-page
- git merge feature/about-page
- git merge feature/contact-page

- git add READMD.md
- git commit -m "รวมคำสั่งทั้งหมด"

- git push origin development