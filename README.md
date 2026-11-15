<p align="center">
  <img src="images/icon.png" width="128" alt="MacFace">
</p>

<h1 align="center">MacFace</h1>

<p align="center">
  <b>มองหน้าจอ → ปลดล็อก Mac</b><br>
  ปลดล็อก Mac ด้วยใบหน้าผ่านกล้องในเครื่อง ไม่ต้องพิมพ์รหัสผ่าน ไม่ต้องเอื้อมไปแตะ Touch ID
</p>

<p align="center">
  <a href="https://github.com/AImunich20/MacFace-releases/releases/latest/download/MacFace.dmg">
    <img src="https://img.shields.io/badge/%E2%AC%87%20%E0%B8%94%E0%B8%B2%E0%B8%A7%E0%B8%99%E0%B9%8C%E0%B9%82%E0%B8%AB%E0%B8%A5%E0%B8%94%20MacFace.dmg-3499ff?style=for-the-badge&logo=apple&logoColor=white" alt="ดาวน์โหลด MacFace.dmg">
  </a>
</p>

<p align="center">
  ฟรี · macOS 15 Sequoia ขึ้นไป · Apple silicon และ Intel · อัปเดตอัตโนมัติ · ข้อมูลใบหน้าไม่ออกจากเครื่อง<br>
  <a href="https://aimunich20.github.io/MacFace-releases/">หน้าเว็บ</a> ·
  <a href="https://github.com/AImunich20/MacFace-releases/releases">ทุกเวอร์ชันและบันทึกการเปลี่ยนแปลง</a> ·
  <a href="#english">English</a>
</p>

---

> [!WARNING]
> **MacFace ไม่ปลอดภัยเท่า Face ID หรือ Touch ID ของ Apple**
>
> กล้อง MacBook เห็นภาพ 2 มิติ ไม่มีเซนเซอร์วัดความลึกแบบ iPhone
> - กันรูปถ่ายที่พิมพ์ออกมาและรูปบนหน้าจอมือถือได้ในระดับหนึ่ง (ต้องเปิดการตรวจ liveness แบบเข้ม)
> - **กันวิดีโอของคุณได้ไม่แน่นอน**
> - macOS ไม่มี API ให้แอปภายนอกอนุมัติการล็อกอิน MacFace จึงปลดล็อกโดยพิมพ์รหัสผ่านที่เก็บไว้ให้บนหน้าจอล็อก
>
> MacFace ช่วยให้สะดวกขึ้น ไม่ได้ทำให้ปลอดภัยขึ้น ใช้เมื่อยอมรับข้อนี้ได้เท่านั้น

## ติดตั้งใน 3 ขั้นตอน

**1. ดาวน์โหลด** [**MacFace.dmg**](https://github.com/AImunich20/MacFace-releases/releases/latest/download/MacFace.dmg) แล้วดับเบิลคลิกเพื่อเปิด

**2. ลาก MacFace ไปวางในโฟลเดอร์ Applications**

**3. เปิด MacFace จาก Applications หรือ Launchpad**

ถ้าขึ้นว่า *"MacFace" can't be opened* หรือ *Apple could not verify…* (เกิดเฉพาะครั้งแรก):

1. กด **Done** หรือ **OK** เพื่อปิดหน้าต่างเตือน
2. เปิด **System Settings → Privacy & Security**
3. เลื่อนลงไปจะเห็น *"MacFace" was blocked…* ให้กด **Open Anyway** แล้วใส่รหัสผ่านเครื่อง
4. กด **Open** อีกครั้ง

ทำแค่ครั้งเดียว การอัปเดตครั้งต่อไปติดตั้งจากในแอปได้เลย

## สิทธิ์ที่ต้องอนุญาต

| สิทธิ์ | ใช้ทำอะไร |
|---|---|
| **Camera** | ดูใบหน้าของคุณ ภาพประมวลผลในหน่วยความจำและไม่ถูกบันทึกลงดิสก์ |
| **Accessibility** | พิมพ์รหัสผ่านลงหน้าจอล็อก |
| **Touch ID** | ปกป้องกุญแจที่ใช้เข้ารหัสข้อมูลใบหน้าและรหัสผ่าน |

## คำถามที่พบบ่อย

<details>
<summary><b>อัปเดตอย่างไร?</b></summary>

MacFace เช็กอัปเดตให้เอง และจะแจ้งเมื่อมีเวอร์ชันใหม่ ถ้าอยากเช็กเองตอนนี้ ให้เปิด **Settings → About → Check for Updates**
</details>

<details>
<summary><b>ข้อมูลของฉันถูกส่งออกไปไหนไหม?</b></summary>

ไม่ การจดจำใบหน้าทำงานในเครื่องทั้งหมดด้วย Vision และ Core ML ข้อมูลใบหน้าและรหัสผ่านถูกเข้ารหัสเก็บในเครื่อง การเชื่อมต่อเดียวที่มีคือการเช็กอัปเดตจากหน้านี้
</details>

<details>
<summary><b>ถอนการติดตั้ง</b></summary>

ออกจาก MacFace แล้วลาก **MacFace** จาก Applications ไปที่ถังขยะ
</details>

---

<a id="english"></a>

## English

**MacFace** unlocks your Mac with your face, using the built-in camera. Recognition runs fully on-device with Vision and Core ML. Your face data and password never leave your Mac.

> **MacFace is not as secure as Face ID or Touch ID.** A Mac webcam sees a flat 2D image. It does not reliably stop a video of you. MacFace unlocks by typing your stored password on the lock screen. It is a convenience feature, not a security upgrade.

**[⬇ Download MacFace.dmg](https://github.com/AImunich20/MacFace-releases/releases/latest/download/MacFace.dmg)** (macOS 15 or later, Apple silicon and Intel)

1. Open the DMG and drag **MacFace** into **Applications**.
2. Open MacFace. If macOS says it can't be opened, close the alert, then go to **System Settings → Privacy & Security → Open Anyway**. You only need to do this once.
3. Follow the setup: allow Camera and Accessibility, enroll your face, and enter your Mac password.

Updates: MacFace checks automatically, or use **Settings → About → Check for Updates**.

MacFace is based on [glance](https://github.com/jonnyoo/glance) by Jonathan Zhou (MIT License).
