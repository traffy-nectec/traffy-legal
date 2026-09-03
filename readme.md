# Traffy Fondue — Legal & Privacy Portal

เว็บพอร์ทัลทางการสำหรับเผยแพร่ **ข้อกำหนดและเงื่อนไขการใช้งาน (Terms of Service)** และ **นโยบายความเป็นส่วนตัว (Privacy Policy)** ของแพลตฟอร์ม **Traffy Fondue** พัฒนาและกำกับดูแลโดย **สำนักงานพัฒนาวิทยาศาสตร์และเทคโนโลยีแห่งชาติ (สวทช.)** ดำเนินการโดย **ศูนย์เทคโนโลยีอิเล็กทรอนิกส์และคอมพิวเตอร์แห่งชาติ (เนคเทค)**

จัดทำขึ้นเพื่อรองรับการตรวจสอบบัญชีทางการ (LINE Official Account Verification / Audit), สอดคล้องตาม พ.ร.บ. คุ้มครองข้อมูลส่วนบุคคล พ.ศ. 2562 (PDPA) และผ่านมาตรฐานการเข้าถึงเว็บไซต์สากล (WCAG 2.1 AA)

---

## 🔗 ลิงก์เอกสารทางการ (Official URLs)

ระบบรองรับทั้งภาษาไทยและภาษาอังกฤษ สามารถนำ Anchor Links ด้านล่างไปกรอกในระบบ LINE Official Account หรือช่องทางบริการอื่นได้ทันที:

| เอกสาร (Document) | ภาษาไทย (TH) | English (EN) |
| :--- | :--- | :--- |
| **Terms of Service** | [ข้อกำหนดการใช้งาน](https://traffy-nectec.github.io/traffy-legal/#terms-th) | [Terms of Service](https://traffy-nectec.github.io/traffy-legal/#terms-en) |
| **Privacy Policy** | [นโยบายความเป็นส่วนตัว](https://traffy-nectec.github.io/traffy-legal/#privacy-th) | [Privacy Policy](https://traffy-nectec.github.io/traffy-legal/#privacy-en) |
| **Right to Erasure** | [แบบฟอร์มขอลบข้อมูล](https://forms.gle/k9Gx9LSveof54WF36) | [Data Erasure Request Form](https://forms.gle/k9Gx9LSveof54WF36) |

*URL หน้าหลักของพอร์ทัล:* `https://traffy-nectec.github.io/traffy-legal/`

---

## 🛡️ สรุปสาระสำคัญด้านกฎหมายและ PDPA (Compliance Highlights)

* **สถานะผู้ควบคุมข้อมูล:** สำนักงานพัฒนาวิทยาศาสตร์และเทคโนโลยีแห่งชาติ (สวทช.) หน่วยงานของรัฐในกำกับกระทรวงการอุดมศึกษา วิทยาศาสตร์ วิจัยและนวัตกรรม (อว.)
* **ฐานทางกฎหมาย (Legal Basis):** ดำเนินการภายใต้ฐานภารกิจเพื่อประโยชน์สาธารณะ (Public Task - ม.24(4)), ฐานประโยชน์อันชอบธรรม (Legitimate Interest - ม.24(5)) และฐานความยินยอม (Consent)
* **การลดปริมาณจัดเก็บข้อมูล (Data Minimization):** ไม่มีการจัดเก็บชื่อโปรไฟล์ (Display Name) ของบัญชี LINE จัดเก็บเฉพาะ LINE User ID, พิกัดสถานที่, รูปภาพหลักฐาน และรายละเอียดปัญหาเมือง
* **กรอบระยะเวลาจัดเก็บ (Data Retention):**
  * *ข้อมูลระบุตัวบุคคล (Identifiable Data):* จัดเก็บสูงสุดไม่เกิน 10 ปี ตามระเบียบงานสารบรรณภาครัฐและอายุความทางกฎหมาย
  * *ข้อมูลสถิติและประวัติปัญหาเมือง (Anonymized Data):* ตัดข้อมูลระบุตัวตนออกทั้งหมด เพื่อให้ สวทช. สามารถจัดเก็บและใช้ประโยชน์เชิงวิจัย (Urban Analytics) และสนับสนุนนโยบายเมืองได้ตลอดไป
* **ข้อจำกัดความรับผิดชอบ (Disclaimer):** ระบุชัดเจนว่า Traffy Fondue เป็นแพลตฟอร์มสื่อกลางประสานงานแจ้งปัญหาเมือง ไม่ใช่หน่วยงานรับแจ้งเหตุด่วนเหตุร้ายหรือการแพทย์ฉุกเฉินเฉพาะหน้า

---

## 📁 โครงสร้างโปรเจกต์ (Project Structure)

```text
traffy-legal/
├── index.html        # หน้า Single Page Application รวม Terms & Privacy ทั้ง TH/EN
├── logo.png          # ไฟล์ภาพตราสัญลักษณ์ Traffy Fondue (ความละเอียด 256x256)
└── README.md         # เอกสารกำกับดูแลและการใช้งานระบบ