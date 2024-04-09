# Medical AI Standard

### Class Description

```
Medical AI Standard
ดร. ราชศักดิ์ สมยานนทนากุล
09/04/2567 09:00 - 12:00
```

### Materials
- [Medical AI Standard.pdf](https://drive.google.com/file/d/1EO5r7qz-oysSZg4ACvDcbOdPPBURyWLl/view)

### My Scratch Paper
- Apple Watch วัด vital sign ได้ค่อนข้างแม่นยำ แต่ยังไม่จดเป็น อุปกรณ์ทางการแพทย์ กับ สปสช. จึงยังนำมาใช้ใน รพ. ไม่ได้
- Algorithm / Model / Robot ต้องผ่านการรับรองจาก อย. ก่อนนำไปใช้ (ผ่าน FDA & ได้ตีพิมพ์ = มีความน่าเชื่อถือ)
- ICD10, Human Phenotype Ontology (HPO), vital signs,  and etc. นำมาใช้ train model
- ระวังเรื่องการทำ augmentation เช่น หัวใจอยู่ด้านซ้าย ไป flip ภาพ แล้วหัวใจกลับด้าน -> model เข้าใจผิด
- เรามอง Software as a Medical Device (SaMD) จะเอาไปใช้ได้ต้องได้รับการประเมินจาก อย.
- ผ่าน AIAT guideline -> ผ่าน lab กลางที่ NECTEC -> มีโอกาสผ่าน อย. ที่ยังไม่มี guideline ที่แน่นอน
- Interpretable AI
- [ Design ] ต้อง declare dataset ได้ 
    - มาจาก clinical ไหม มีแหล่งที่มาที่น่าเชื่อถือไหม
    - ครอบคลุมเท่าไหร่ ทั้งประเทศไหม เพศ อายุ เชื้อชาติ demography
    - เทียบกับ baseline (gold standard) เช่น ให้หมอ 5 คนที่เป็น expertist มา label dataset แล้วเทียบกับ predicted label จาก model เรา
- [ Build ] ใช้แนวทางตามการขึ้นทะเบียนเครื่องมือแพทย์
    - มีการขอ standard เช่น ISO จาก lab กลางที่ NECTEC
- [ Test ]
- [ Use ]
- [ Monitor ]
- [ Review ]
- เราพยายามสร้างกรอบ เช่น ISO ต่าง ๆ เพื่อไปผ่าน อย. ในด่านสุดท้าย
- ช่วยหมอในการ screening เพื่อ recommend ให้หมอ make final decision