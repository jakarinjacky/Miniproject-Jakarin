
````markdown
# Mini Project Jakarin

## 📌 Overview
โปรเจคนี้เป็น **Mini Project** สำหรับเรียนรู้และใช้งาน **Discrete Math** และ **Number Theory** โดยสร้างเครื่องมือ interactive ผ่าน **เว็บแอป Streamlit**  

ฟังก์ชันที่มีในโปรเจค:  
1. **Count of k-combinations with repetition**  
   - คำนวณจำนวนวิธีในการเลือก `k` สิ่งจาก `n` สิ่งโดยสามารถเลือกซ้ำได้  
   - ตัวอย่าง: เลือกผลไม้ 4 ผลจากผลไม้ 3 ชนิด  

2. **Identity Block Matrix Creator**  
   - สร้างเมทริกซ์ขนาดใหญ่ที่ประกอบด้วยหลายบล็อก identity matrix  
   - ใช้สำหรับงาน Linear Algebra, Control Systems หรือ Block Operations  

3. **ตรวจสอบ pseudoprime (base b)**  
   - ตรวจสอบว่าจำนวนคี่ `n` เป็น pseudoprime สำหรับฐาน `b` หรือไม่  
   - ตัวอย่าง: 341 เป็น pseudoprime base 2  

---

## 🛠 Technology Used
- **Programming Language:** Python  
- **Web Framework:** Streamlit  
- **Libraries:**  
  - `numpy` สำหรับสร้างและจัดการ Matrix  
  - `math` สำหรับคำนวณ Factorial และ Combinations  

---

## 💻 Installation

1. **Clone โปรเจคนี้**
```bash
git clone <your-repo-url>
cd <project-folder>
````

2. **ติดตั้ง Python libraries**

```bash
pip install streamlit numpy
```

---

## 🚀 Usage

รันเว็บแอปด้วยคำสั่ง:

```bash
streamlit run main.py
```

เว็บจะเปิดใน **browser** ให้คุณกรอกค่าและใช้งาน interactive tools ได้ทันที

---

## 🖼 UI Features

* **Banner สีเขียวบนสุด** แสดงชื่อโปรเจค
* **Tabs แยกฟังก์ชัน**
* **สูตร Math แสดงด้วย LaTeX**
* **Matrix แสดง DataFrame** อ่านง่าย
* **ผลลัพธ์ interactive** พร้อมข้อความ success / warning
* **Footer** แสดงเทคโนโลยีที่ใช้

---

## 📌 Example Usage

1. **Count of k-combinations**:

   * Input: n = 3, k = 4
   * Output: 15

2. **Identity Block Matrix**:

   * Input: block_size = 3, num_blocks = 2
   * Output: 6x6 matrix with two identity blocks

3. **Pseudoprime Checker**:

   * Input: n = 341, b = 2
   * Output: True (341 is a pseudoprime base 2)

---

## 📄 License

This project is licensed under MIT License.

```

---

ถ้าต้องการ ผมสามารถ **เขียน README.md เวอร์ชันสวย ๆ** ที่มี **รูปภาพตัวอย่างเว็บ, ปุ่มสีเขียว, screenshot, และตัวอย่างผลลัพธ์** ให้ผู้ใช้เห็นภาพชัดเจนได้เลย  

คุณอยากให้ผมทำ README.md แบบมี **รูปประกอบเว็บและตัวอย่างผลลัพธ์** ด้วยไหม?
```
