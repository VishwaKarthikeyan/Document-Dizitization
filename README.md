

**Document Digitization**

Document digitization is the process of converting physical documents or images into digital format, enabling easier storage, retrieval, and manipulation of the content. It involves several steps aimed at transforming analog information into machine-readable data, often utilizing Optical Character Recognition (OCR) technology.

Here's a breakdown of the steps involved in document digitization:

**Image Clarity Enhancement**: Enhances image quality to improve OCR accuracy.

  ![image](https://github.com/VishwaKarthikeyan/OCR/assets/100937600/027a1323-a17a-4855-b3c0-446cef7cfc6e)



  •	Histogram equalization                                    
  
  •	Image sharpening (Laplacian filter)
  
  •	Wiener filter
  
  •	Image Super-resolution

**Layout/Object Detection**: Identifies text regions and objects in images/documents.

![image](https://github.com/VishwaKarthikeyan/OCR/assets/100937600/126162e6-a6dd-445a-93f7-b9310077d192)


•	Layout XLM	

•	Yolov8

•	Azure Form Recognizer

•	Layout Parser

**OCR**: Converts text images into machine-readable text.

![image](https://github.com/VishwaKarthikeyan/OCR/assets/100937600/54abb327-7178-452f-ac5c-5f729ddfb687)


•	CRNN (Custom) 

•	[Textsnake](https://github.com/princewang1994/TextSnake.pytorch)

•	GCP OCR

•	Azure OCR

•	[PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR/blob/release/2.7/README_en.md)

•	[MMOCR](https://github.com/open-mmlab/mmocr)


**OCR Post Processing**: Refines OCR results to enhance accuracy and consistency.

•	Regex

•	Dictionary matches

•	Word-level clustering


**OCR Validation**: Assesses OCR output quality and accuracy metrics.

![image](https://github.com/VishwaKarthikeyan/OCR/assets/100937600/574b106f-0bae-4eba-b125-a6c220cf9fd0)


•	Word length, permissible character check

•	Triangulations on key-value pairs

•	Accuracy validation on Character Error Rate (CER), Word Error Rate (WER)


**Deployment**

Training mode – Normal, Distributed, Mixed Precision

Training Environment – Linux GPU/CPU, Linux DCU, Windows GPU/CPU, macOS

Compression – Prune, Quantization, Distillation

Inference and Deployment – Python/C++ Inference, Python/C++ Serving, OpenCL ARM GPU,Paddle2ONNX, PaddleCloud , ARM CPU, Jetson, Paddle.js


**Solutions and Algorithms**
  
![image](https://github.com/VishwaKarthikeyan/OCR/assets/100937600/7fa64a40-ed32-4856-9ec1-647598af4dbf)

![image](https://github.com/VishwaKarthikeyan/OCR/assets/100937600/2caa2d45-72ff-447b-bd63-2384d0649975)


**Applications**

Financial Scene – Forms, Bills

Industrial Scene – Watt hour meter, License plate

Educational Scene- Handwriting, Formula

Medical Scene – Laboratory test Report

**Examples**

![image](https://github.com/VishwaKarthikeyan/OCR/assets/100937600/cefa57f3-e2c5-40b1-b0ec-f28214bee11b)

![image](https://github.com/VishwaKarthikeyan/OCR/assets/100937600/74086a1b-4b8b-41ab-84e5-42e7c7495579)

![image](https://github.com/VishwaKarthikeyan/OCR/assets/100937600/57cfba9a-5add-4a5b-b675-17a2474696ca)





