# Civil Engineering Concrete Analysis & Material Database Portal

ชุดเครื่องมือประมวลผลบนเว็บ (Web-based Applications) เพื่อการวิเคราะห์พฤติกรรมระยะยาวของคอนกรีตและการออกแบบส่วนผสม โดยบูรณาการมาตรฐานการทำนายสากลและมาตรฐานประเทศไทย (มยผ. 1332-25) ร่วมกับฐานข้อมูลคุณสมบัติมวลรวมท้องถิ่น

---

## 🚀 Key Modules & Applications

### 1. Concrete Shrinkage Comparator & Predictor
* **Multi-Model Evaluation:** เปรียบเทียบการทำนายการหดตัว 5 โมเดลพร้อมกัน (DPT 1332-25, B4 RILEM TC-242, ACI 209R-92, CEB MC90-99, GL2000)
* **Local Material Calibration:** เชื่อมโยงพฤติกรรมการหดตัวกับคุณสมบัติการดูดซึมน้ำของหิน ($\phi_R$) และพื้นที่ผิวจำเพาะ ($S_R$)
* **Batch Analysis:** ระบบประมวลผลข้อมูลแล็บขนาดใหญ่แบบหลายชุดข้อมูล พร้อมดัชนีทางสถิติ (RMSE, $V_{CE}$, $\omega_{BP}$)

### 2. Concrete Compressive Creep Analysis
* คำนวณและประเมินพฤติกรรมการคืบตัวของคอนกรีตภายใต้หน่วยแรงอัดคงที่ระยะยาว
* ประเมินค่า Creep Coefficient ($\phi$) และ Compliance Function ($J$) สำหรับงานออกแบบคอนกรีตอัดแรง (Prestressed Concrete) และการเสียรูปของโครงสร้างสะพาน

### 3. Compressive Strength Evolution
* โมเดลวิเคราะห์และทำนายการพัฒนากำลังอัดตามอายุคอนกรีต ($f'_{c}$)
* รองรับอิทธิพลของอัตราส่วนน้ำต่อวัสดุประสาน ($w/b$), ชนิดปูนซีเมนต์, และวัสดุประสานทดแทน (Fly Ash, Limestone Powder)

### 4. Thai Aggregate Characteristics Database
* ฐานข้อมูลคุณสมบัติทางกายภาพและวิศวกรรมของมวลรวมหยาบและละเอียดในประเทศไทย
* รวบรวมข้อมูลจำเพาะ เช่น ความหนาแน่น, ความถ่วงจำเพาะ (SG), เปอร์เซ็นต์การดูดซึมน้ำ (Absorption), ปริมาตรรูพรุนสะสมระดับนาโน (Porosity 2–50 nm) จากแหล่งผลิตหลักทั่วทุกภูมิภาค (หินปูน, แกรนิต, บะซอลต์, กรวดแม่น้ำ)

---

## 🛠️ Technology Stack
* **Frontend:** Vanilla HTML5, JavaScript (ES6+)
* **Styling:** Tailwind CSS
* **Data Visualization:** Plotly.js
* **Hosting:** GitHub Pages (Serverless & Zero-cost)
