# OCR / Analog Meter Reading Project 

An AMR (automatic meter reading) project for reading analog meters, built with openCV+Python using basic OCR and image processing techniques.

## **OCR** 

OCR engines convert images containing typed, handwritten or printed text into machine-encoded text. Their most common use are PDF scanners, allowing to read text from printed papers. The aim is to digitise these texts, so that they can be electronically edited for AI, computer vision or pattern recognition problems and can be further used for research.

**for more info:** https://github.com/kba/awesome-ocr

### **Some OCR Applications:**

* Project Gutenberg
* Google Books
* Automatic number-plate recognition
* Passport Recognition
* Traffic-Sign Recognition (TSR)
* ...

## **AMR**

AMR is a sub-section of OCR engines, built primarily to read electricity, gas and water meters. The AMR technologies allow energy companies or their customers to capture meter images using a mobile device. This practice is cheaper and more feasible than manual on-site reading, and easier to deploy - in the short/medium term - than the replacement of old meters.

### **Two main categories:**

**1.Analog:** Cyclometer and dial displays

**2.Digital:** Electronic display and smart meters

### **Difficulties in AMR:**

* Poor file resolution
* Blurry images, particularly motion blur
* Small or large scale
* Poor lighting and low contrast due to overexposure, reflection or shadows
* An object obscuring (dirt, broken glass etc.)

## **Technologies**

* CNN
  * Train: [SVHN (The Street View House Numbers)](http://ufldl.stanford.edu/housenumbers/)
  * Test: [Analog Meter Images](https://github.com/ayseceyda/analog-meter-reading-openCV/tree/main/images) 
  * Test Image Values: [.xlsx](https://github.com/ayseceyda/analog-meter-reading-openCV)
  
  **[big thanks to yamato/yamaton](https://github.com/yamaton/water-meter-reading)**
  
* Python
* Keras
* Tensorflow
* OpenCV
* Pandas

## **Accuracy** 

#### **%57 - %65**

Accuracy may increase/decrease due to changes in the pre-processing steps or the image quality (brightness, luminance, contrast etc.)

## **Result**

![croped](https://user-images.githubusercontent.com/29989590/111771499-d5f89780-88bc-11eb-8406-fb434d147356.png)
