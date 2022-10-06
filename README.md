# Chest X-Ray classification for tuberculosis and lung cancer  by machine learning algorith
## Senior Project 

    Pretrained คือ การใช้ weight จากโมเดลที่เทรนมาแล้ว นำมาเป็น initial weight หรือ weight เริ่มต้นของการเทรนโมเดลด้วยชุดข้อมูลของเรา (CXR img) 
    แล้วเทรนโมเดลเพื่อหา weight ใหม่เฉพาะ neural network เพื่อให้ได้ weight ที่เหมาะสมกับชุดข้อมูลของเรา
    
    
    รูปในเล่ม หน้า 8 
    
    โมเดล DenseNet201 มีทั้งหมด 709 layers แบ่งเป็น ชั้นของ Convolutional Neural Network (CNN) 707 layers และ neural network 2 layers 
    โมเดล 
    
    แต่ละเลเยอร์ ใน CNN จะมี initial weight หรือ weight เริ่มต้นมาด้วย 
    
    Pretrained คือ การใช้ weight จากโมเดลที่เทรนมาแล้ว นำมาเป็น initial weight หรือ weight เริ่มต้นของการเทรนโมเดลด้วยชุดข้อมูลของเรา (CXR img) 
    แล้วเทรนโมเดลเพื่อหา weight ใหม่เฉพาะ neural network เพื่อให้ได้ weight ที่เหมาะสมกับชุดข้อมูลของเรา
    
    Finetune 
