---
layout: page
title: ดูตัวอย่างและตรวจสอบ
order: 3
locale: th
---

ดูตัวอย่างหน้า AMP ได้เหมือนกับการดูตัวอย่างเว็บไซต์ HTML อื่นๆ ที่ไม่มีการเปลี่ยนแปลง ซึ่งไม่ต้องมีขั้นตอนการสร้างหรือการดำเนินการล่วงหน้าใดๆ โดยดำเนินการอย่างใดอย่างหนึ่งต่อไปนี้

  - **เปิดหน้าเว็บจากระบบไฟล์บนเบราว์เซอร์โดยตรง** (อิลิเมนต์บางอย่างอาจไม่ทำงานเนื่องจาก XMLHttpRequests ดำเนินการไม่สำเร็จ)
  - **ใช้เว็บเซิร์ฟเวอร์ภายใน เช่น Apache 2 หรือ Nginx**
    *(เคล็ดลับ: สำหรับเว็บเซิร์ฟเวอร์ที่รวดเร็ว ให้เรียกใช้ `python -m SimpleHTTPServer`)*

จากนั้น ให้ตรวจสอบว่าหน้า AMP ของคุณ**เป็นหน้า AMP ที่ถูกต้อง** หรือไม่สามารถค้นหาและเผยแพร่บนแพลตฟอร์มของบุคคลที่สาม เช่น Google Search หากต้องการตรวจสอบ ให้ดำเนินการดังนี้

  1. เปิดหน้าเว็บของคุณในเบราว์เซอร์
  1. เพิ่ม "`#development=1`" ลงใน URL เช่น `http://localhost:8000/released.amp.html#development=1`
  1. เปิด[คอนโซลของ Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/debug/console/) แล้วตรวจสอบข้อผิดพลาด

[เรียนรู้เพิ่มเติมเกี่ยวกับการตรวจสอบ](/docs/guides/validate.html) และสิ่งที่ควรทำเมื่อพบข้อผิดพลาด

{% include button.html title="ไปยังขั้นตอนที่ 5" link="/docs/get_started/create/prepare_for_discovery.th.html" %}