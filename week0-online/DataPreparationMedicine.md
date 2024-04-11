# Data preparation and usecases for AI in Medicine

### Class Description

```
Data preparation and usecases for AI in Medicine
นพ.ปิยะฤทธิ์ อิทธิชัยวงศ์
11/04/2567 13:00 - 16:00
```

### Materials
- [Slide](https://drive.google.com/drive/folders/1Xadye7GBKq9rSJDbycp3KgY1XQFQ3RK7)

## My Scratch Paper
- Underfitting - cannot predict everything
- Overfitting - can only predict what it has seen
- Balanced - can predict unseen data (generalization)
- Imbalanced Data -> แก้ด้วย K-Fold (Cross Validation) -> reduce bias
- บางทีแบ่ง fold แล้วก็ยังได้ imbalanced class ใน fold นั้น ๆ จึงต้อง Shuffle ก่อนจะ Split เป็น fold
- Stratified sampling จะ split fold โดยคำนึงถึง อัตราส่วนของ class ทำให้แต่ละ fold มี class ที่ balance กันมากยิ่งขึ้น
- Stratified Shuffle Split
- Sensitivity ค่าความไว & Specificity ค่าความจำเพาะ
- Average Precision (AP) & (mAP)
- Positive Prediction Value (PPV)
- Negative Prediction Value (NPV)
- Periperal Blood Smear (PBS) แพทย์ใช้ microscope เสียเวลา เลยใช้เครื่องที่ไส้ในเป็น deep learning แต่แพง ราว ๆ 5 ล้านต่อเครื่อง ข้อเสียของเครื่องคือ detect พวก abnormal cell ไม่ค่อยแม่น แพทย์ก็ต้องใช้ microscope re-check อยู่ดี
- เล่นกับ real clinical data ต้องขอ consent จริยธรรมวิจัย ก่อน
- LLM ยังมี hallucination but LLM with RAG ช่วยได้
- ระวัง shortcut learning -> ลอง Grad-CAM ดูว่า make sense ไหม
- Data Anonymisation -> ใช้ syntetic image แทนได้ ไม่ติด PDPA
