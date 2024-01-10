|course|workshop|certificate|
|------|--------|-----------|
|xPore | [gmm](https://github.com/Chanoknunkal/PMU-B-PersonalAI/blob/main/xpore_(1).ipynb)     |[📃]  
|biosignal| [brain signal](https://github.com/Chanoknunkal/PMU-B-PersonalAI/blob/main/model.py)|[📃]
|plagiarism|[code clone](https://github.com/Chanoknunkal/PMU-B-PersonalAI/blob/main/PMU_B_CodingAI_CodeCloneDetection_Workshop.ipynb)|[📃]
mental disorder| [NLP](https://github.com/Chanoknunkal/PMU-B-PersonalAI/blob/main/PMU_B_CodingAI_CodeCloneDetection_Workshop.ipynb)|[📃]
BiTnet|[Effientnet](https://github.com/Chanoknunkal/PMU-B-PersonalAI/blob/main/Copy_of_E_san_coding.ipynb)|[📃](https://powerclass.org/tutor-certificate-3?cert_hash=8e627b84dabec27f)
arresting criminal|[YOLO](https://github.com/Chanoknunkal/PMU-B-PersonalAI/blob/main/Copy_of_Train_Yolov8_Object_Detection_on_Custom_Dataset.ipynb)|[📃][![IkfpyHOT13-1236d0576f804d2a](https://github.com/Chanoknunkal/PMU-B-PersonalAI/assets/156036800/87a6f351-994e-4cb1-b36b-d7eb5aca637f)](https://powerclass.org/tutor-certificate-3?cert_hash=1236d0576f804d2a)



# PMU-B-PersonalAI
Chanoknun Poolpherm Triamudom Grade 11
# xPore: An AI-Powered App for Bioinformaticians
Project: xPore ซอฟท์แวร์ที่ช่วยเปรียบเทียบตำแหน่งของลำดับเบสบนสาย RNA ของเซลล์ใด ๆ เช่น เปรียบเทียบระหว่าง RNA ของผู้ป่วยมะเร็งกับคนปกติ ว่าตำแหน่งใดบนสาย RNA ที่มีลักษณะโมเลกุลไม่เหมือนกัน โดยการใช้ข้อมูลสัญญาณไฟฟ้าที่มาจาก Nanopore sequencer ซึ่งเป็นเครื่องมือแรกและเครื่องมือชนิดเดียวในตอนนี้สามารถ sequence ลำดับเบสของสาย RNA ได้โดยตรงอย่างมีประสิทธิภาพ
ถูกพัฒนาขึ้นมาเพื่อ
1. ช่วยนักชีวสารสนเทศในการหาตำแหน่งและหาปริมาณของ RNA modification บนลำดับเบส RNA ที่ไม่เหมือนกันระหว่าง samples ใดๆ ซึ่งผลลัพธ์นี้จะช่วยเป็นสมมติฐานให้กับนักวิจัยในแลปในการทำการทดลองต่อไปว่า ตำแหน่งที่ไม่เหมือนกันนั้นจะเกี่ยวข้องกับการวินิจฉัยโรค การผลิตวัคซีนหรือยา หรือการแยกแยะประเภทของไวรัส อย่างไร
2. เซลล์มนุษย์จะมีลำดับเบสหลายล้านตำแหน่ง ดังนั้นการมีซอฟท์แวร์ที่ประมวลผลได้รวดเร็วและเชื่อถือได้ จะทำให้ประหยัดเวลาในการทดลองในแลปจากหลายวันมาเป็นไม่กี่ชั่วโมง และประหยัดในเรื่องของต้นทุนและทรัพยากรในการทำแลปในห้องทดลองได้
ในปัจจุบัน xPore เป็น Python package ที่เปิดให้ใช้ฟรี v1.0 ตั้งแต่ปี 2021 ตอนนี้ได้พัฒนาเป็น v2.1 โดยมีผู้ download ไปแล้วกว่า 27,000 ครั้ง
สามารถดูรายละเอียดได้ที่ https://github.com/GoekeLab/xpore
# Learning from Biosignal
Project: TinySleepNet แบบจำลองการเรียนรู้เชิงลึก (Deep Learning Model) สำหรับวิเคราะห์การนอน (Sleep Stage Scoring) ด้วยคลื่นสัญญาณสมอง ภายใต้โครงการ Learning from Biosignals
ถูกพัฒนาขึ้นมาเพื่อ
1. เพิ่มประสิทธิภาพให้กับการสกัดคุณลักษณะเฉพาะจากคลื่นสมองเพื่อเพิ่มประสิทธิภาพให้กับการวิเคราะห์การนอน
2. สร้างต้นแบบของแบบจำลองมีสามารถนำไปติดตั้งที่อุปกรณ์พกพาที่สามารถนำไปวิเคราะห์การนอนขณะที่คนไข้อยู่ที่บ้านได้
3. ช่วยลดงานของผู้เชี่ยวชาญในการวิเคราะห์สัญญาณคลื่นสมองเพื่อให้คะแนนการนอน
ในปัจจุบันองค์ความรู้ที่ได้จากการพัฒนา TinySleepNet ได้ถูกนำไปต่อยอดและอ้างอิงถึงโดยนักวิจัยทั่วโลกมากกว่า 100 ครั้ง และได้ถูกเผยแพร่ใน Github
# AI for detecting code plagiarism
Project: Code Clone Detector – ระบบ AI สำหรับช่วยตรวจวัดความเหมือนของโค้ดและตรวจจับการคัดลอกโค้ด
ถูกพัฒนาขึ้นมาเพื่อ
1. ช่วยลดงานของนักพัฒนาซอฟต์แวร์ (software developer) ในค้นหาโค้ดที่เหมือนกัน เพื่อปรับปรุงคุณภาพของซอฟต์แวร์ตนเอง
2. ช่วยลดงานของครู/อาจารย์ที่สอนวิชาเกี่ยวกับการเขียนโปรแกรม เพื่อให้ตรวจจับการลอกงานของนักเรียน/นักศึกษา (plagiarism) ได้อย่างรวดเร็วแม่นยำ
เนื่องจากใช้ระบบ AI ในการช่วยตรวจจับ ทำให้สามารถค้นหาโค้ดที่เหมือนกันได้ แม้จะมีการแก้ไขไปบางส่วน
ในปัจจุบันระบบ Merry เปิดให้นำไปทดลองใช้งานได้ฟรี
ติดตามรายละเอียดได้ทาง
https://github.com/MUICT-SERU/SP2019-07-CodeCloneDetection
# BiTNet: AI for diagnosing ultrasound image
Project: BiTNet ระบบ AI สำหรับช่วยคัดกรองความผิดปกติในช่องท้องส่วนบน ด้วยภาพถ่ายอัลตราซาวน์
ถูกพัฒนาขึ้นมาเพื่อ
       1. ช่วยลดงานของรังสีแพทย์ในการวินิจฉัยภาพถ่ายอัลตราซาวน์ ที่ถูกส่งมาสอบถามจากแพทย์เวชปฏิบัติที่ทำหน้าที่คัดกรองผู้ป่วยมะเร๋งท่อน้ำดีที่หน้างาน
       2. ช่วยเพิ่มความมั่นใจในการวินิจฉัยของแพทย์เวชปฏิบัติในการวินิจฉัยความผิดปกติอีกด้วย
ความผิดปกติที่สามารถวินิจฉัยได้มีกว่า 25 ความผิดปกติ ตั้งแต่ ไขมันพอกตับ ตับแข็ง นิ่วในถุงน้ำดี ฯลฯ
ในปัจจุบันระบบ BiTNet ถูกนำมาใช้จริงแล้วในโรงพยาบาลเครือข่ายของสถาบันวิจัยมะเร็งท่อน้ำดีกว่า 200 หน่วย ทั้งภาคอีสาน ภาคเหนือ และ สปป.ลาว
โดยระบบ BiTNet ได้รับรางวัล
       – รองชนะเลิศรางวัลนวัตกรรมแห่งชาติ 2021
       – รองชนะเลิศรางวัล Thailand ICT Award 2023
และเป็นตัวแทนของไทยไปแข่ง Asia Pacific ICT Award ที่ประเทศฮ่องกง ปลายปี 2023 นี้
ติดตามรายละเอียดได้ทาง
https://tohnperfect.github.io/BiTNet/
# Mental disorder detection from social media data
Research project: Predicting mental health disorders from social media data เป็นการทำนายโรคซึมเศร้าจากข้อมูลการโพสบนสื่อสังคมออนไลน์
ถูกพัฒนาขึ้นเพื่อ
1. เพื่อทำนายโรคซึมเศร้าจากข้อมูลสื่อสังคมออนไลน์ ซึ่งเริ่มต้นด้วยการรวบรวมข้อมูลจากแพลตฟอร์มสื่อสังคมออนไลน์ เช่น เฟสบุ๊ค, ทวิตเตอร์, อินสตาแกรม หรือเว็บไซต์อื่น ๆ ที่ผู้คนใช้ในการแสดงความรู้สึกและความคิดเห็นของพวกเขาเกี่ยวกับสถานะจิตใจของตนเอง
2. หลังจากที่เราสามารถทำนายโรคซึมเศร้าได้ด้วยความแม่นยำ เราสามารถใช้ข้อมูลนี้เพื่อรวบรวมกลุ่มผู้ที่เสี่ยงต่อโรคซึมเศร้าและให้การสนับสนุนที่เหมาะสมได้
ติดตามรายละเอียดได้ทาง
https://www.jmir.org/2017/6/e228/
Code: https://colab.research.google.com/drive/1Pp4PQeaie5lGILqgAa1ztYi4J-9RHh7_?usp=sharing#scrollTo=GZO3jQAwBh7H
# AI for arresting criminals
โครงการ: การวิจัยและพัฒนาระบบการติดตามจับกุมคนร้ายด้วยเทคโนโลยีปัญญาประดิษฐ์ (Research and Development of Tracking Systems for Arresting Criminals Using Artificial Intelligence)
โครงการนี้ได้รับการพัฒนาขึ้นมาเพื่อ
1. เพิ่มประสิทธิภาพของเจ้าหน้าที่ตำรวจในการจัดเก็บและตรวจสอบข้อมูลอาชญากรรมผ่านระบบการติดตามจับกุมคนร้ายด้วยเทคโนโลยีปัญญาประดิษฐ์
2. สร้างความเชื่อมั่นและรักษาความปลอดภัยให้กับประชาชน โดยใช้เทคโนโลยีกล้องวงจรปิด (CCTV) เพื่อช่วยเจ้าหน้าที่ตำรวจในการเฝ้าระวังการกระทำความผิดและบันทึกหลักฐาน
3. พัฒนาระบบแจ้งเตือน ตรวจจับ ติดตามและรู้จำบุคคลหรือรถต้องสงสัยด้วยเทคโนโลยีปัญญาประดิษฐ์
รายละเอียดเพิ่มเติมเกี่ยวกับการตรวจจับและระบุตำแหน่งเหตุการณ์ผิดปกติที่มีความถูกต้องสูง สามารถอ่านได้จากบทความได้ทาง
https://www.sciencedirect.com/science/article/pii/S0167865521003925
# Self-introduction Video
[![watch the video(https://youtu.be/Tmq7ClFuzXY)]
