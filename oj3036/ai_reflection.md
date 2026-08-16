# บันทึก Reflection การใช้ AI

ใช้ไฟล์นี้เฉพาะเมื่อมีการใช้ AI กับโจทย์ OJ ที่เป็น learning-log-required เท่านั้น

ให้ copy template นี้ แล้วเปลี่ยนชื่อไฟล์เป็น:

```text
ai_reflection.md
```

เขียน reflection นี้ด้วยคำพูดของตนเอง

ห้ามวาง AI conversation ทั้งหมด

ห้ามให้ AI เขียน reflection นี้แทนคุณ

AI อาจช่วยตรวจ grammar, formatting หรือความชัดเจนได้ หลังจากที่คุณเขียน reflection ของตนเองแล้ว

---

## 1. ข้อมูล OJ

| Item | Answer |
|---|---|
| OJ problem number/title | OJ3036 - [LEARNING LOGS] ปราสาท |
| OJ submission ID, if submitted | 602386 |
| OJ status | Pass |

---

## 2. เครื่องมือ AI ที่ใช้

เขียนชื่อเครื่องมือ AI ที่ใช้

ตัวอย่าง:

```text
ChatGPT
Claude
Gemini
ChatGPT Codex / OpenAI Codex / Codex CLI
Claude Code
Other: ...
```

My answer:

```text
Gemini
```

---

## 3. การตรวจสอบนโยบายการใช้ AI ของรายวิชา

ตอบหัวข้อนี้อย่างซื่อสัตย์

หัวข้อนี้ยืนยันว่าคุณได้ทำตาม AI workflow ของรายวิชาก่อนและระหว่างใช้ AI

| Statement | Yes / No / Not Applicable | Short note |
|---|---|---|
| I read the relevant workflow before using AI. | Yes |  |
| I used `instructions/COURSE_AI_INSTRUCTIONS.md`, `instructions/AGENTS.md`, or manually followed the course AI instructions if the tool did not support custom instructions. | No |  |
| I wrote my own problem understanding before asking AI for help. | Yes |  |
| I wrote my own first plan before asking AI for help. | Yes |  |
| I used AI as a coach, reviewer, debugger, or test-case helper, not as a full-answer generator. | Yes |  |

ถ้าตอบ "No" ในข้อใด ให้อธิบายเหตุผล:

```text
พิมพ์patternที่ตัวเองหามาเอง แล้วให้AIช่วยแนะวิธีว่าควรจะเริ่มต้นอย่างไร แต่ไม่ได้บอกว่าเป็นโจทย์การเขียนโปรแกรมจึงไม่ได้ใช้instructions AIเลยตอบมาแบบกว้างๆ
```

---

## 4. ฉันถาม AI ให้ช่วยอะไร

อธิบายสั้น ๆ ว่าถาม AI ให้ช่วยเรื่องอะไร

ห้ามวาง chat log ทั้งหมด

ตัวอย่าง:

- ฉันถาม AI ให้ช่วยอธิบายโจทย์ด้วยภาษาที่เข้าใจง่ายขึ้น
- ฉันถาม AI ให้ช่วย review แผนแรกของฉัน
- ฉันถาม AI ให้ช่วยหา bug ใน code
- ฉันถาม AI ให้ช่วยเสนอ test cases
- ฉันถาม AI ให้อธิบายว่าทำไม output ของฉันต่างจาก expected output

My answer:

```text
ฉันถามAIเรื่องการวิเตราห์pattern ว่าถ้าpatternเป็นแบบนี้แล้วเลข1000000จะต้องเท่ากับเท่าไหร่ ตามข้อความนี้
1=0

2=2
3=1
4=2

5=4
6=3
7=4
8=3
9=4

10=6
11=5
12=6
13=5
14=6
15=5
16=6

17=8
18=7
19=8
20=7
21=8
22=7
23=8
24=7
25=8

26=10
27=9
28=10
29=9
30=10
31=9
32=10
33=9
34=10
35=9
36=10

37=12
38=11
39=12
40=11
41=12
42=11
43=12
44=11
45=12
46=11
47=12
48=11
49=12
แบบนี้ไปเรื่อยๆ แล้ว100000จะเท่ากับเท่าไหร่
```

---

## 5. AI ช่วยให้ฉันสังเกตอะไร

เขียนว่า AI ช่วยให้คุณสังเกตอะไร

ตัวอย่าง:

- ความเข้าใจผิดเกี่ยวกับโจทย์
- condition ที่ขาดไป
- bug ในการอ่าน input
- edge case
- ปัญหา syntax ของ Python
- ปัญหา output formatting

My answer:

```text
AI ช่วยให้ฉันสังเกตว่า หมายเลขห้องแรกของแต่ละชั้นจะเป็น ((ชั้น-1)**2)+1 เช่น ชั้นที่5 ห้องแรกจะเป็น((5-1)**2)+1 ซึ่งคือ17 ตามที่โจทย์กำหนด แล้วผลลัพธ์ตัวแรกคือ2*(ชั้น-1)
```

---

## 6. ฉันตรวจสอบหรือแก้อะไรด้วยตนเอง

เขียนว่าหลังจากได้รับความช่วยเหลือจาก AI คุณตรวจสอบ ทดสอบ หรือแก้อะไรด้วยตนเอง

ตัวอย่าง:

- ฉันตรวจ input format ใน OJ problem อีกครั้ง
- ฉันทดสอบ code ใน VS Code
- ฉันเปรียบเทียบ expected output กับ actual output
- ฉันแก้ loop condition ด้วยตนเอง
- ฉันไม่ใช้บางคำแนะนำของ AI เพราะไม่ตรงกับ constraints ของโจทย์
- ฉันปรับคำแนะนำของ AI ให้เป็น code ที่ฉันเข้าใจเอง

My answer:

```text
คิดวิธีหาชั้นโดยใช้math.sqrt(), ปัดเศษขึ้นโดยใช้math.ceil() และสร้างเงื่อนไขตรวจสอบชั้นและห้องหมายเลขคู่และคี่ที่มีค่ามากน้อยสลับกันตามชั้น
```

---

## 7. ฉันได้เรียนรู้อะไร

เขียน 2-4 ประโยคเกี่ยวกับสิ่งที่ได้เรียนรู้จากโจทย์นี้และจากกระบวนการใช้ AI ช่วย

ให้เน้นการเรียนรู้ของตนเอง

ห้ามเขียนแค่ว่า "I learned coding" หรือ "AI helped me."

My answer:

```text
ฉันได้เรียนรู้การสังเกตและการจับpattern โดยต้องหาจุดให้ถูกและสร้างเงื่อนไขให้จำแนกผลลัพธ์ได้
```

---

## 8. คำรับรองของนักศึกษา

ตอบอย่างซื่อสัตย์

| Statement | Yes / No |
|---|---|
| I wrote this reflection in my own words. | Yes |
| This reflection describes my real AI use. | Yes |
| I checked AI's suggestions before using them. | Yes |
| I can explain my final code. | Yes |
| I did not ask AI to write this reflection for me. | Yes |
