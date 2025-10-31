# โปรเจค 1: การบวก - ไข่ไก่ของแม่ 🥚

## แบบฝึก 1 ไข่ไก่
```c
I (1000) main_task: Started on CPU0
I (1020) main_task: Calling app_main()
I (1030) EGGS_MATH: 🥚 เริ่มต้นโปรแกรมนับไข่ไก่ของแม่ 🥚
I (1030) EGGS_MATH: =====================================
I (1030) EGGS_MATH: 📖 โจทย์:
I (1030) EGGS_MATH:    แม่มีไข่ไก่อยู่แล้ว: 8 ฟอง
I (1030) EGGS_MATH:    เมื่อเช้าไก่ออกไข่เพิ่ม: 3 ฟอง
I (1030) EGGS_MATH:    ❓ วันนี้แม่มีไข่ไก่รวมกี่ฟอง?
I (1030) EGGS_MATH: 
I (1330) EGGS_MATH: 🧮 ขั้นตอนการคิด:
I (1330) EGGS_MATH:    ไข่ไก่ที่มีอยู่ + ไข่ไก่ที่ออกใหม่
I (1330) EGGS_MATH:    = 8 + 3
I (1330) EGGS_MATH:    = 11 ฟอง
I (1330) EGGS_MATH:
I (1330) EGGS_MATH: 🦆 และแม่มีไข่เป็ด: 3 ฟอง
I (1330) EGGS_MATH: 🥚 ไข่ทั้งหมด (ไก่+เป็ด): 14 ฟอง
I (1330) EGGS_MATH: ✅ คำตอบ:
I (1330) EGGS_MATH:    วันนี้แม่มีไข่ไก่ทั้งหมด 11 ฟอง
I (1330) EGGS_MATH:    ไข่รวมทั้งหมด (ไก่ + เป็ด) คือ 14 ฟอง
I (1330) EGGS_MATH:
I (1530) EGGS_MATH: 🎨 ภาพประกอบ:
I (1530) EGGS_MATH:    ไข่เดิม: 🥚🥚🥚🥚🥚🥚🥚🥚 (8 ฟอง)
I (1530) EGGS_MATH:    ไข่ใหม่: 🥚🥚🥚 (3 ฟอง)
I (1530) EGGS_MATH:    รวมไก่: 🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚 (11 ฟอง)
I (1530) EGGS_MATH:    ไข่เป็ด: 🥚🥚🥚 (3 ฟอง)
I (1530) EGGS_MATH:    รวมทั้งหมด: 🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚 (14 ฟอง)
I (1730) EGGS_MATH:
I (1730) EGGS_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (1730) EGGS_MATH:    ถ้าแม่มีไข่ 7 ฟอง และไก่ออกไข่ 3 ฟอง
I (1730) EGGS_MATH:    จะได้ไข่ทั้งหมด 7 + 3 = 10 ฟอง
I (1730) EGGS_MATH:
I (1930) EGGS_MATH:    ถ้าแม่มีไข่ 10 ฟอง และไก่ออกไข่ 5 ฟอง
I (1930) EGGS_MATH:    จะได้ไข่ทั้งหมด 10 + 5 = 15 ฟอง
I (1930) EGGS_MATH:
I (2130) EGGS_MATH: 📚 สิ่งที่เรียนรู้:
I (2130) EGGS_MATH:    1. การบวกเลข (Addition): a + b = c
I (2130) EGGS_MATH:    2. การใช้ตัวแปร (Variables) เก็บค่า
I (2130) EGGS_MATH:    3. การแสดงผลด้วย ESP_LOGI
I (2130) EGGS_MATH:    4. การแก้โจทย์แบบมีขั้นตอน
I (2330) EGGS_MATH:
I (2330) EGGS_MATH: 🎉 จบโปรแกรมนับไข่ไก่ของแม่!
I (2330) EGGS_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 02_subtraction_toys
I (2530) main_task: Returned from app_main()
```

---

## แบบฝึก 2 เพิ่มไข่เป็ด
```
I (1000) main_task: Started on CPU0
I (1020) main_task: Calling app_main()
I (1030) EGGS_MATH: 🥚 เริ่มต้นโปรแกรมนับไข่ไก่ของแม่ 🥚
I (1030) EGGS_MATH: =====================================
I (1030) EGGS_MATH: 📖 โจทย์:
I (1030) EGGS_MATH:    แม่มีไข่ไก่อยู่แล้ว: 8 ฟอง
I (1030) EGGS_MATH:    เมื่อเช้าไก่ออกไข่เพิ่ม: 3 ฟอง
I (1030) EGGS_MATH:    ❓ วันนี้แม่มีไข่ไก่รวมกี่ฟอง?
I (1030) EGGS_MATH: 
I (1330) EGGS_MATH: 🧮 ขั้นตอนการคิด:
I (1330) EGGS_MATH:    ไข่ไก่ที่มีอยู่ + ไข่ไก่ที่ออกใหม่
I (1330) EGGS_MATH:    = 8 + 3
I (1330) EGGS_MATH:    = 11 ฟอง
I (1330) EGGS_MATH:
I (1330) EGGS_MATH: 🦆 และแม่มีไข่เป็ด: 3 ฟอง
I (1330) EGGS_MATH: 🥚 ไข่ทั้งหมด (ไก่+เป็ด): 14 ฟอง
I (1330) EGGS_MATH: ✅ คำตอบ:
I (1330) EGGS_MATH:    วันนี้แม่มีไข่ไก่ทั้งหมด 11 ฟอง
I (1330) EGGS_MATH:    ไข่รวมทั้งหมด (ไก่ + เป็ด) คือ 14 ฟอง
I (1530) EGGS_MATH: 🎨 ภาพประกอบ:
I (1530) EGGS_MATH:    ไข่เดิม: 🥚🥚🥚🥚🥚🥚🥚🥚 (8 ฟอง)
I (1530) EGGS_MATH:    ไข่ใหม่: 🥚🥚🥚 (3 ฟอง)
I (1530) EGGS_MATH:    รวมไก่: 🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚 (11 ฟอง)
I (1530) EGGS_MATH:    ไข่เป็ด: 🥚🥚🥚 (3 ฟอง)
I (1530) EGGS_MATH:    รวมทั้งหมด: 🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚 (14 ฟอง)
I (1730) EGGS_MATH:
I (1730) EGGS_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (1730) EGGS_MATH:    ถ้าแม่มีไข่ 7 ฟอง และไก่ออกไข่ 3 ฟอง
I (1730) EGGS_MATH:    จะได้ไข่ทั้งหมด 7 + 3 = 10 ฟอง
I (1730) EGGS_MATH:
I (1930) EGGS_MATH:    ถ้าแม่มีไข่ 10 ฟอง และไก่ออกไข่ 5 ฟอง
I (1930) EGGS_MATH:    จะได้ไข่ทั้งหมด 10 + 5 = 15 ฟอง
I (1930) EGGS_MATH:
I (2130) EGGS_MATH: 📚 สิ่งที่เรียนรู้:
I (2130) EGGS_MATH:    1. การบวกเลข (Addition): a + b = c
I (2130) EGGS_MATH:    2. การใช้ตัวแปร (Variables) เก็บค่า
I (2130) EGGS_MATH:    3. การแสดงผลด้วย ESP_LOGI
I (2130) EGGS_MATH:    4. การแก้โจทย์แบบมีขั้นตอน
I (2330) EGGS_MATH:
I (2330) EGGS_MATH: 🎉 จบโปรแกรมนับไข่ไก่ของแม่!
I (2330) EGGS_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 02_subtraction_toys
I (2530) main_task: Returned from app_main()

```

---

## แบบฝึก 3 แอปเปิ้ล
```
I (1000) APPLE_MATH: 🧮 ขั้นตอนการคิด:
I (1200) APPLE_MATH:    แอปเปิ้ลที่มีอยู่ + แอปเปิ้ลที่เก็บเพิ่ม
I (1200) APPLE_MATH:    = 3 + 5
I (1200) APPLE_MATH:    = 8 ผล
I (1200) APPLE_MATH: 
I (1400) APPLE_MATH: ✅ คำตอบ:
I (1400) APPLE_MATH:    ตอนนี้ในตะกร้ามีแอปเปิ้ลทั้งหมด 8 ผล
I (1400) APPLE_MATH:
I (1600) APPLE_MATH: 🎨 ภาพประกอบ:
I (1600) APPLE_MATH:    แอปเปิ้ลเดิม: 🍎🍎🍎 (3 ผล)
I (1600) APPLE_MATH:    แอปเปิ้ลใหม่: 🍎🍎🍎🍎🍎 (5 ผล)
I (1600) APPLE_MATH:    รวม: 🍎🍎🍎🍎🍎🍎🍎🍎 (8 ผล)
I (1800) APPLE_MATH:
I (1800) APPLE_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (1800) APPLE_MATH:    ถ้ามีแอปเปิ้ล 7 ผล และเก็บเพิ่ม 3 ผล
I (1800) APPLE_MATH:    จะได้แอปเปิ้ลทั้งหมด 7 + 3 = 10 ผล
I (2000) APPLE_MATH:
I (2000) APPLE_MATH:    ถ้ามีแอปเปิ้ล 10 ผล และเก็บเพิ่ม 5 ผล
I (2000) APPLE_MATH:    จะได้แอปเปิ้ลทั้งหมด 10 + 5 = 15 ผล
I (2000) APPLE_MATH:
I (2200) APPLE_MATH: 📚 สิ่งที่เรียนรู้:
I (2200) APPLE_MATH:    1. การบวกเลข (Addition): a + b = c
I (2200) APPLE_MATH:    2. การใช้ตัวแปร (Variables) เก็บค่า
I (2200) APPLE_MATH:    3. การแสดงผลด้วย ESP_LOGI
I (2200) APPLE_MATH:    4. การแก้โจทย์แบบมีขั้นตอน
I (2400) APPLE_MATH:
I (2400) APPLE_MATH: 🎉 จบโปรแกรมนับแอปเปิ้ลในตะกร้า!
I (2400) APPLE_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 02_subtraction_oranges
I (2600) main_task: Returned from app_main()

```
