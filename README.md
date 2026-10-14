# Be Cutzo · ดาวน์โหลด

**ฟรี 300 เครดิต สำหรับ 100 บัญชีแรก** · โปรแกรมช่วยตัดคลิปพูดภาษาไทยด้วย AI (Public Beta)

## [กดตรงนี้เพื่อไปหน้าดาวน์โหลดเวอร์ชันล่าสุด](https://github.com/BeCutzo/be-cutzo-releases/releases/latest)

## วิธีติดตั้ง · 3 ขั้นตอน

### 1. โหลดไฟล์ของเครื่องคุณ

ในหน้าดาวน์โหลด กดไฟล์ตามเครื่องของคุณ

| เครื่องของคุณ | ไฟล์ที่ต้องโหลด | ขนาด |
|:--|:--|:--|
| **Windows 10 / 11** | `Be-Cutzo-Setup-(เลขเวอร์ชัน).exe` | ราว 1.3 GB |
| **Mac ชิป Apple (M1 ขึ้นไป)** | `Be-Cutzo-(เลขเวอร์ชัน)-arm64.dmg` | ราว 0.2 GB |

ไฟล์อื่น (`latest.yml`, `.blockmap`, `Source code`) ไม่ต้องโหลด · Mac รุ่น Intel ยังใช้ไม่ได้

### 2. ติดตั้ง

#### Windows

1. ดับเบิลคลิกไฟล์ที่โหลดมา
2. ถ้าขึ้นหน้าต่างสีน้ำเงิน **"Windows protected your PC"** ให้กดคำว่า **More info** แล้วกดปุ่ม **Run anyway**  
   *ขึ้นเพราะโปรแกรมยังไม่ได้ซื้อใบรับรองจาก Microsoft ไม่ใช่ไวรัส*
3. กด **Next** ไปจนถึง **Install** แล้วกด **Finish** โปรแกรมจะเปิดขึ้นมา

#### Mac

1. ดับเบิลคลิกไฟล์ `.dmg` แล้วลากไอคอน **Be Cutzo** ไปวางบนโฟลเดอร์ **Applications**
2. เปิดโปรแกรม **Terminal** (กด Command + Space พิมพ์ `Terminal` แล้วกด Enter)
3. คัดลอกบรรทัดนี้ไปวางใน Terminal แล้วกด Enter **ทำครั้งเดียว**
   ```
   xattr -cr "/Applications/Be Cutzo.app"
   ```
   *ต้องทำเพราะโปรแกรมยังไม่ได้ลงทะเบียนกับ Apple ถ้าข้ามขั้นนี้ Mac จะขึ้นว่าไฟล์เสีย (damaged) และเปิดไม่ได้*
4. เปิด **Be Cutzo** จากโฟลเดอร์ Applications

### 3. เปิดครั้งแรก

1. โปรแกรมจะโหลด **โมเดลถอดเสียงราว 3 GB** ครั้งเดียว มีแถบบอกความคืบหน้า ถ้าเน็ตหลุดกด **ลองใหม่** จะโหลดต่อจากเดิม
2. กด **สมัครสมาชิก** แล้วกรอกชื่อ อีเมล รหัสผ่าน
3. กรอก **รหัส 6 หลัก** ที่ส่งไปทางอีเมล (ส่งจาก becutzohq@gmail.com ถ้าไม่เห็นให้ดูในโฟลเดอร์สแปม)
4. ได้ **300 เครดิตฟรี** เริ่มใช้ได้เลย

> **ต้องมี:** พื้นที่ว่างราว 6 GB และอินเทอร์เน็ต  
> **ติดปัญหา:** กดปุ่ม **รายงาน** ในโปรแกรม หรืออีเมล becutzohq@gmail.com

## อัปเดต

โปรแกรมตรวจหาเวอร์ชันใหม่จากหน้านี้ทุกครั้งที่เปิด และถามว่าจะอัปเดตไหม
บน Windows กด **ใช่** แล้วโปรแกรมโหลดและติดตั้งให้เอง บน Mac ปุ่มจะพามาหน้านี้ให้โหลดไฟล์ใหม่ลงทับ

---

ที่นี่มีแค่ไฟล์ติดตั้ง ซอร์สโค้ดของโปรแกรมไม่ได้อยู่ในหน้านี้ · ติดต่อ becutzohq@gmail.com

*English:* this repository only hosts Be Cutzo installers; the source code is private.
Download from the [latest release](https://github.com/BeCutzo/be-cutzo-releases/releases/latest):
the `.exe` for Windows 10/11 (64-bit), or the `-arm64.dmg` for Apple-silicon Macs (unsigned — run
`xattr -cr "/Applications/Be Cutzo.app"` once after installing). Contact: becutzohq@gmail.com
