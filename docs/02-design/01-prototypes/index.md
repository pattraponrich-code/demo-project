# 01 - Prototypes

เก็บ **ต้นแบบหน้าตาของระบบ (UI/UX Prototype)** เช่น

- Wireframe / mockup ของแต่ละหน้าจอ
- User flow และ navigation flow
- Design system เบื้องต้น เช่น สี ฟอนต์ คอมโพเนนต์หลัก

ใช้สำหรับสื่อสารและตกลงหน้าตาของระบบก่อนลงมือพัฒนาจริง โดยอ้างอิงความต้องการจาก [[../../01-requirements/01-spec/index|01-spec]] และส่งต่อรายละเอียดเชิงระบบให้ [[../02-technical/index|02-technical]]

## รายการ User Journey

| Flow | Actor หลัก | ไฟล์ | อ้างอิงจาก Requirement |
|---|---|---|---|
| ลูกค้าสั่งกาแฟที่โต๊ะผ่าน QR Code | ลูกค้า, บาริสต้า | [[table-ordering-qr-journey\|table-ordering-qr-journey]] | [[../../01-requirements/01-spec/20260802-001-table-ordering-qr\|001 - ระบบสั่งกาแฟที่โต๊ะผ่าน QR Code]] |
| ลูกค้าขอใบเสร็จ/ใบกำกับภาษี (ให้ความยินยอมตาม PDPA) | ลูกค้า | [[receipt-tax-invoice-consent-journey\|receipt-tax-invoice-consent-journey]] | [[../../01-requirements/01-spec/20260802-002-system-log-pdpa\|002 - การเก็บ Log ของระบบ และการปฏิบัติตาม PDPA เบื้องต้น]] |
