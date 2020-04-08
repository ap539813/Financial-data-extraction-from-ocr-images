# Financial-data-extraction-from-ocr-images
This project contains a deterministic approach to extract the financial tables from the plane texts gathered from the ocr of images of financial documents.
Problem Statement Focus: To check for NLP and Python capability to extract data elements from the financial statement documents.

# My score was 205 out of 500 and that was 4th place
![](sample%20images/hcl_score.png)

# Data to be provided – 
* Training & Development Set - 500 Text files (OCR output of images)
	
# Sample Data to be Extracted
* Highlighted text on the image is required to be extracted

![](sample%20images/sample1.png)


### Fields to be extracted are:
* Current Assets : 51,700
* Creditors: amounts falling due within one year : 55,505
* Net current liabilities : (3,805)
* Total assets less current liabilities : (3,805)
* Accruals and deferred income : (500)
* Net liabilities : (4,305)
* Capital and reserves : (4,305)

#### Expected Output:
{“Current assets":"51700","Creditors:amounts falling due within one year":"-55505","Net current liabilities":"-3805","Total assets less current liabilities":"-3805","Accurals and deferred income":"-500","Net liabilities":"-4305","Capital and reserves":"-4305"}

![](sample%20images/sample2.png)

### Fields to be extracted are: 
* Fixed asset :  15837
* Intangible assets : 9423
* Tangible assets : 6414
* Current Assets : 236,183
* Debtors: amounts falling due within one year : 113,831
* Cash at bank and in hand : 122,352
* Creditors: amounts falling due within one year : (110,924)
* Net current assets : 125,259 
* Net assets : 141,096
* Capital and reserves: -
* Called up share capital : 70,587
* Profit and loss accounts 70,509
* Shareholders funds : 141,096

#### Expected Output:
{"Intangible Assets":"9423","Tangible assets":"6414","Fixed assets":"nan","nan":"15837","Debtors: amounts falling due within one year":"113831","Cash at bank and in hand":"122352","Current assests":"nan","nan":"236183","Creditors: amounts tailing due within one year":"-110924","Net current assets":"125259","Net assets":"141096","Capital and reserves":"nan","Called up share capital":"70587","Profit and loss account":"70509","Shareholders’ funds":"141096"}

## Please note, data only for year 2019 is to be extracted.
