# Action Recognition

### Class Description

```
Action Recognition
ดร.ศีตภา วัชราภินชัย (อาจารย์เหมียว)
11/04/2567 09:30 - 12:30
```

### Materials
- [Slide](https://drive.google.com/drive/folders/1G-vY8np4Mn-DnA9E8y0R9Vu4thob3qJT)
- [Colab](https://colab.research.google.com/drive/1-G360NeJl1N-XMhLvlIKRPixfZik3lPt)

## My Scratch Paper
- Type of Actions
    - Single Person -> Gesture, Action
    - Human-Human Interaction -> Shakehand
    - Human-Object Interaction -> Kick Football
    - Group Activity -> Meeting
- [ What ] Action Reconition (classification)
- [ When ] Temporal Action Localization - Untrimmed VDO -> action start & end time
- [ Where ] Spatio Temporal Action Localization - Untrimmed VDO -> action start & end time + bounding box / segmentation at every frame
- Image is spatial data (เชิงพื้นที่)
- temporal คือมีเวลาเข้ามาเกี่ยว
- VDO is temporal (เวลาไหน) & spatial (ตำแหน่งไหน)
- AR (Action Recognition), 
- TAP (Temporal Action Proposal) -> frame
- SAP (Spatiotemporal Action Proposal) -> tube
- Scene Detection เอา frame_t+1 ลบด้วย frame_t แล้วดูว่าถึง threshold ที่จะสรุปว่า scene เปลี่ยนไหม
- Temporal Action Proposal Generation -> only start & end time, no classification
- Evaluate ใช้ IOU ในเชิงแกนเวลา temporal
- คำนวณหา Motion from Image eg. Optical Flow หาตำแหน่งการเคลื่อนที่ ลบ frame แล้วดูว่า pixel ไหนเคลื่อนที่
- Two Stream Architecture = Spatial stream + Temporal Stream -> เอา single frame ผ่าน convnet 1 stream ส่วนอีก stream ใช้ optical flow
- 3D Convolution ใช้ 3D Kernel ทำ VDO convolution
- high-frame rate อาจเปลือง ก็เลยไปใช้ skeleton data แทน
- challenges in AR - different viewpoint, action similarities and variations, action length