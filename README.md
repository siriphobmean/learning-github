# Learning-Github
for Learning use Github by BorntoDev

link : https://youtu.be/fOlDcMStMXE?si=SZ6m4jAaE8V2TkxA

# Note
- Commit คล้ายกับการสร้างุจด Save Point ใน Game
- in terminal: git checkout -b new-name-branch //for create branch
- in terminal: git branch -D name-brach //for delete branch
- in terminal: git checkout name-branch //for switch branch ex. checkout main, checkout mean
- in terminal: git commit -m "text"

---

- Push คือการ Sync ข้อมูลจากในตัวเครื่องไปยังหน้าเว็บ Github
- in terminal: git push origin main

---

- Pull Request คือการส่งตัว branch ที่แยกออกมากลับเข้าสู่ main
- in terminal: git pull

---

- การ Merge ถ้าเข้า main โดยตรงจะไม่ผ่านการอนุญาตจากใคร แต่ถ้าใช้ pull request จะเป็นเหมือนการสร้างเว็บบอร์ดสำหรับคุยกัน แล้วจะมีคนที่ได้รับหน้าที่ให้อนุมัติ มาทำการ merge จาก brach แยกสู่ main
- interminal: git merge name-branch --no-ff

---

- Issue คือประเด็น ปัญหา... จะเหมือนเว็บบอร์ดมากกว่า pull request แต่ pr จะเป็นลักษณะประมาณว่ากำลังจะรวมโค้ดกันแล้ว ช่วยมาดูหน่อย
- in terminal: git checkout -b issue-number(task) 
- กรณีของ Open คือ ประเด็นหรือปัญหานั้น ยังคุยหรือจัดการไม่เสร็จ
- กรณีของ Close คือ ประเด็นหรือปัญหานั้น คุยหรือจัดการเสร็จเรียบร้อยแล้ว