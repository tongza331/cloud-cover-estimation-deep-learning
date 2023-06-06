# cloud-cover-estimation-deep-learning
## โครงงานนี้เป็นส่วนหนึ่งของรายวิชา CPE401, CPE402 @ KMUTT
### Short abstract
โครงงานนี้มีจุดประสงค์เพื่อใช้ deep learning (image segmentation task) ในการตรวจจับเมฆและทำการคำนวณหาปริมาณเมฆจากรูปภาพนั้น ซึ่งปริมาณเมฆเป็นตัวแปรที่สำคัญในการพยากรณ์การผลิตกำลังไฟฟ้าของ Photovaltaic cell
### Tech stack:
- Tensoflow/Keras (version<=2.10)
- SegmentationModel API (Tensorflow base)

### Experimental details:
- epoch: 60
- optimizer: adamW
- model: U-NET
- backbone: ResNet34

## แนวทางในการพัฒนาโครงงาน
- ใช้ Image Regression ในการหาค่าปริมาณเมฆจากรูปภาพ
