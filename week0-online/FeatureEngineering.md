# Feature Engineering Techiques

### Class Description

```
Feature Engineering Techiques
ดร.วรินทร์ วัฒนพรพรหม
10/04/2567 09:00 - 12:00
```

### Materials
- [Slide](https://drive.google.com/drive/folders/1FVoSnuwfPGSEV15E8IczzZX8WzOgtdDh)

## My Scratch Paper
- Decision Tree (explainable - in term of data separation) ไม่เก่งเมื่อเจอ noise เยอะ ๆ, ตัดสินใจผิดที่ node ไหน ก็จะเดินไป invalid path แล้ว
- KNN (explainable - in term of geometry)
- Naive Bayes (explainable - in term of probability)
- Bias ทำให้ linear predictor มีปัญหา
- Varince ทำให้ decision tree เลี้ยวผิดทาง
- high dimension อาจทำให้ network ทำงานได้แย่ลง บางทีเราเลยทำ feature selection เอา information คล้าย ๆ กันออก หรืออาจทำ dimensional reduction เพื่อลดมิติ
- บางทีอาจไม่ได้ตัดทิ้ง แต่รวม feature เป็น feature เดียว ให้ more informative
- add new attribute only if they bring new information
- binary string -> hamming distance ใช้ OR gate ออกใน 1 clock -> ประหยัด (Google ใช้ของถูก)
- พวก cosine sim. , euclidean dist. มี more computational cost
- naive bayes, decision tree สามารถ extract rule ออกมาได้
- RFM Analysis (Recency, Frequency, Monetary) วิเคราะห์ว่า ลูกค้ามาซื้อของเรา ครั้งสุดท้ายตอนไหน ถี่แค่ไหน ปริมาณเท่าไหร่ (บัตร stamp ครบทุกช่อง ชานมฟรี 1 แก้ว)
- calculate RFM value ด้วยการหา Recency, Frequency, Monetary แล้วปรับให้อยู่ scale เดียวกัน จากนั้นนำมา concat กัน หรือคิดเป็น score
- feature selection -> information gain, correlation, greedy search (add & remove)
- feature selection ทำกับ trainset แล้วค่อย apply testset ทีหลัง