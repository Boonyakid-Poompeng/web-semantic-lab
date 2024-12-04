# web-semantic-lab
โปรเจคนี้เป็นส่วนหนึ่งของวิชา Web Frontend Development 

## รายละเอียด 
- การใช้ Semantic HTML
- Form Validation
- ARIA Labels

## git command used in this lab
git config --global user.name "Boonyakid"
git config --global user.email 66160252@go.buu.ac.th
git clone Boonyakid-Poompeng/web-semantic-lab
git add README.md
git commit -m “รายละเอียด”
git push
git checkout -b development
git add .
git commit -m “สร้างโครงสร้างโปรเจคเริ่มต้น”
git checkout -b feature/homepage
( แก้ไข index และ contact )
git add index.html
git add contact.html
git commit -m "สร้างโครงสร้างเริ่มต้นของโปรเจค"
( แก้ไข index )
git add index.html
git commit -m “เพิ่ม header และ nav ในหน้าหลัก”
( แก้ไข index ) 
git add index.html
git commit -m “เพิ่มส่วน main และ article ในหน้าหลัก”
( แก้ไข index )
git add index.html
git commit -m "เพิ่ม aside และ footer ในหน้าหลัก"
git checkout -b feature/contact
git add contact.html
git commit -m "สร้างโครงสร้างพื้นฐานหน้าติดต่อ"
( แก้ไข contact )
git add contact.html
git commit -m "เพิ่มฟอร์มพื้นฐานในหน้าติดต่อ"
( แก้ไข contact )
git add contact.html
git commit -m "เพิ่ม validation ในฟอร์มติดต่อ"
( แก้ไข contact )
git add contact.html
git commit -m "เพิ่ม ARIA labels ในฟอร์ม"
( แก้ไข contact )
git add contact.html
git commit -m "เพิ่ม ARIA landmarks ในการนําทาง"
( แก้ไข index W3C )
git add contact.html
git commit -m "แก้ไข index จาก W3C "
( แก้ไข contact W3C )
git add contact.html
git commit -m "แก้ไข contact จาก W3C "
git checkout development
git merge feature/homepage
git merge feature/contact