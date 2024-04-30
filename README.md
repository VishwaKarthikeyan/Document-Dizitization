

## **Document Digitization**

Document digitization is the process of converting physical documents or images into digital format, enabling easier storage, retrieval, and manipulation of the content. It involves several steps aimed at transforming analog information into machine-readable data, often utilizing Optical Character Recognition (OCR) technology.

![image](https://github.com/VishwaKarthikeyan/Document-Dizitization/assets/100937600/f3c06c4f-21c1-4a10-83a3-3936dae9484a)


Here's a breakdown of the steps involved in document digitization:

**Image Clarity Enhancement**: Enhances image quality to improve OCR accuracy.

![image](https://github.com/VishwaKarthikeyan/Document-Dizitization/assets/100937600/767e866b-cfc9-4b63-b169-ae5e648d6e5e)




  •	Histogram equalization                                    
  
  •	Image sharpening (Laplacian filter)
  
  •	Wiener filter
  
  •	Image Super-resolution

**Layout/Object Detection**: Identifies text regions and objects in images/documents.

![image](https://github.com/VishwaKarthikeyan/Document-Dizitization/assets/100937600/be61cf31-c91b-4892-9804-55d9a5e01321)



•	Layout XLM	

•	Yolov8

•	Azure Form Recognizer

•	Layout Parser

**OCR**: Converts text images into machine-readable text.

![image](https://github.com/VishwaKarthikeyan/Document-Dizitization/assets/100937600/31cf83b5-e020-4a3e-9f2c-e7299f160a98)



•	CRNN (Custom)

•	[Textsnake](https://github.com/princewang1994/TextSnake.pytorch)

•	[PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR/blob/release/2.7/README_en.md)

•	[MMOCR](https://github.com/open-mmlab/mmocr)

•	GCP OCR

•	Azure OCR


**OCR Post Processing**: Refines OCR results to enhance accuracy and consistency.

•	Regex

•	Dictionary matches

•	Word-level clustering


**OCR Validation**: Assesses OCR output quality and accuracy metrics.

![image](https://github.com/VishwaKarthikeyan/Document-Dizitization/assets/100937600/9cd34493-92e3-4272-86c3-c380c2b6a6c6)



•	Word length, permissible character check

•	Triangulations on key-value pairs

•	Accuracy validation on Character Error Rate (CER), Word Error Rate (WER)


### **Deployment**

•	Training mode – Normal, Distributed, Mixed Precision

•	Training Environment – Linux GPU/CPU, Linux DCU, Windows GPU/CPU, macOS

•	Compression – Prune, Quantization, Distillation

•	Inference and Deployment – Python/C++ Inference, Python/C++ Serving, OpenCL ARM GPU,Paddle2ONNX, PaddleCloud , ARM CPU, Jetson, Paddle.js



### **Solutions and Algorithms**
  
![image](https://github.com/VishwaKarthikeyan/Document-Dizitization/assets/100937600/b321c7a3-f379-49b9-abf1-1edcc477ef10)


![image](https://github.com/VishwaKarthikeyan/Document-Dizitization/assets/100937600/7d1c3d1f-9608-44e4-8c8c-fc96bd572a0c)



### **Applications**

•	Financial Scene – Forms, Bills

•	Industrial Scene – Watt hour meter, License plate

•	Educational Scene- Handwriting, Formula

•	Medical Scene – Laboratory test Report


### **Examples**

![image](https://github.com/VishwaKarthikeyan/Document-Dizitization/assets/100937600/8774127e-471f-4818-861b-19c78a0ab7aa)


![image](https://github.com/VishwaKarthikeyan/Document-Dizitization/assets/100937600/fa14ffa8-66ef-494c-bc11-337180408e5a)


![image](https://github.com/VishwaKarthikeyan/Document-Dizitization/assets/100937600/858fbcde-f728-4895-a601-0dab05617e33)






