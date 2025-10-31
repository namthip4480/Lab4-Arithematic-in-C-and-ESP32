# แบบฝึกหัด 1  เปลี่ยนจำนวนคุกกี้
```
I (5643) spi_flash: flash io: dio
I (5659) main_task: Started on CPU0
I (5669) main_task: Calling app_main()
I (5679) COOKIES_MATH: 🍪 เริ่มต้นโปรแกรมแบ่งคุกกี้ 🍪
I (5689) COOKIES_MATH: ================================
I (5699) COOKIES_MATH: 📖 โจทย์:
I (5709) COOKIES_MATH:    มีคุกกี้: 24 ชิ้น
I (5719) COOKIES_MATH:    จะแบ่งให้เพื่อน: 6 คน
I (5729) COOKIES_MATH:    ❓ แต่ละคนได้คุกกี้กี่ชิ้น?
I (5739) COOKIES_MATH:
I (5939) COOKIES_MATH: 🧮 ขั้นตอนการคิด:
I (5949) COOKIES_MATH:    คุกกี้ทั้งหมด ÷ จำนวนเพื่อน
I (5959) COOKIES_MATH:    = 24 ÷ 6
I (5969) COOKIES_MATH:    = 4 ชิ้นต่อคน
I (5979) COOKIES_MATH:
I (5989) COOKIES_MATH: ✅ คำตอบ:
I (5999) COOKIES_MATH:    แต่ละคนได้คุกกี้ 4 ชิ้น
I (6009) COOKIES_MATH:    แบ่งได้พอดี ไม่มีเหลือ
I (6019) COOKIES_MATH:
I (6029) COOKIES_MATH: 🎨 ภาพประกอบการแบ่ง:
I (6039) COOKIES_MATH:    คุกกี้ทั้งหมด: 🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪 (24 ชิ้น)
I (6049) COOKIES_MATH:
I (6059) COOKIES_MATH:    เพื่อนคนที่ 1: 
I (6069) COOKIES_MATH: 🍪🍪🍪🍪 (4 ชิ้น)
...
I (6459) COOKIES_MATH: 🎉 จบโปรแกรมแบ่งคุกกี้!
I (6469) COOKIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 05_mixed_shopping
I (6769) main_task: Returned from app_main()

```
---

# แบบฝึกหัด 2 เพิ่มการตรวจสอบหารลงตัว
```
I (5913) spi_flash: flash io: dio
I (5932) main_task: Started on CPU0
I (5942) main_task: Calling app_main()
I (5952) COOKIES_MATH: 🍪 เริ่มต้นโปรแกรมแบ่งคุกกี้ 🍪
I (5962) COOKIES_MATH: ================================
I (5972) COOKIES_MATH: 📖 โจทย์:
I (5982) COOKIES_MATH:    มีคุกกี้: 24 ชิ้น
I (5992) COOKIES_MATH:    จะแบ่งให้เพื่อน: 6 คน
I (6002) COOKIES_MATH:    ❓ แต่ละคนได้คุกกี้กี่ชิ้น?
I (6012) COOKIES_MATH:
I (6212) COOKIES_MATH: 🧮 ขั้นตอนการคิด:
I (6222) COOKIES_MATH:    คุกกี้ทั้งหมด ÷ จำนวนเพื่อน
I (6232) COOKIES_MATH:    = 24 ÷ 6
I (6242) COOKIES_MATH:    = 4 ชิ้นต่อคน
I (6252) COOKIES_MATH:
I (6262) COOKIES_MATH: ✅ หารลงตัว! ทุกคนได้เท่ากัน
I (6272) COOKIES_MATH: ✅ คำตอบ:
I (6282) COOKIES_MATH:    แต่ละคนได้คุกกี้ 4 ชิ้น
I (6292) COOKIES_MATH:    แบ่งได้พอดี ไม่มีเหลือ
I (6302) COOKIES_MATH:
I (6312) COOKIES_MATH: 📚 สิ่งที่เรียนรู้:
I (6322) COOKIES_MATH:    1. การหารเลข (Division): a ÷ b = c
I (6332) COOKIES_MATH:    2. การใช้ Modulo operator (%) หาเศษ
I (6342) COOKIES_MATH:    3. การตรวจสอบการหารด้วยศูนย์
I (6352) COOKIES_MATH:    4. ความแตกต่างระหว่างหารลงตัวและไม่ลงตัว
I (6362) COOKIES_MATH:    5. การจัดการกรณีพิเศษ (Error Handling)
I (6372) COOKIES_MATH:
I (6382) COOKIES_MATH: 🎉 จบโปรแกรมแบ่งคุกกี้!
I (6392) COOKIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 05_mixed_shopping
I (6642) main_task: Returned from app_main()

```
---

# แบบฝึกหัด 3 หาจำนวนเพื่อนที่เหมาะสม
```
I (6101) spi_flash: flash io: dio
I (6121) main_task: Started on CPU0
I (6131) main_task: Calling app_main()
I (6141) COOKIES_MATH: 🍪 เริ่มต้นโปรแกรมแบ่งคุกกี้ 🍪
I (6151) COOKIES_MATH: ================================
I (6161) COOKIES_MATH: 📖 โจทย์:
I (6171) COOKIES_MATH:    มีคุกกี้: 24 ชิ้น
I (6181) COOKIES_MATH:    จะแบ่งให้เพื่อน: 6 คน
I (6191) COOKIES_MATH:    ❓ แต่ละคนได้คุกกี้กี่ชิ้น?
I (6201) COOKIES_MATH:
I (6251) COOKIES_MATH: 🧮 ขั้นตอนการคิด:
I (6261) COOKIES_MATH:    คุกกี้ทั้งหมด ÷ จำนวนเพื่อน
I (6271) COOKIES_MATH:    = 24 ÷ 6
I (6281) COOKIES_MATH:    = 4 ชิ้นต่อคน
I (6291) COOKIES_MATH:
I (6301) COOKIES_MATH: ✅ หารลงตัว! ทุกคนได้เท่ากัน
I (6311) COOKIES_MATH: ✅ คำตอบ:
I (6321) COOKIES_MATH:    แต่ละคนได้คุกกี้ 4 ชิ้น
I (6331) COOKIES_MATH:    แบ่งได้พอดี ไม่มีเหลือ
I (6341) COOKIES_MATH:
I (6351) COOKIES_MATH: 🔍 คุกกี้ 30 ชิ้น หารลงตัวกับ:
I (6361) COOKIES_MATH:    ✅ 1 คน → คนละ 30 ชิ้น
I (6371) COOKIES_MATH:    ✅ 2 คน → คนละ 15 ชิ้น
I (6381) COOKIES_MATH:    ✅ 3 คน → คนละ 10 ชิ้น
I (6391) COOKIES_MATH:    ✅ 5 คน → คนละ 6 ชิ้น
I (6401) COOKIES_MATH:    ✅ 6 คน → คนละ 5 ชิ้น
I (6411) COOKIES_MATH:    ✅ 10 คน → คนละ 3 ชิ้น
I (6421) COOKIES_MATH:
I (6431) COOKIES_MATH: 📚 สิ่งที่เรียนรู้:
I (6441) COOKIES_MATH:    1. การหารเลข (Division): a ÷ b = c
I (6451) COOKIES_MATH:    2. การใช้ Modulo operator (%) หาเศษ
I (6461) COOKIES_MATH:    3. การตรวจสอบการหารด้วยศูนย์
I (6471) COOKIES_MATH:    4. ความแตกต่างระหว่างหารลงตัวและไม่ลงตัว
I (6481) COOKIES_MATH:    5. การจัดการกรณีพิเศษ (Error Handling)
I (6491) COOKIES_MATH:
I (6501) COOKIES_MATH: 🎉 จบโปรแกรมแบ่งคุกกี้!
I (6511) COOKIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 05_mixed_shopping
I (6641) main_task: Returned from app_main()

```
---
