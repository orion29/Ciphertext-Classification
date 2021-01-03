# Ciphertext-Classification

## Dataset:
     Training Set:  2000  ciphertexts each 1344 byte long
     Validation Set:  1000  cipher texts each 1344 byte long  


## Classes

###  Blowfish
Blowfish is a symmetric-key block cipher, designed in 1993 by Bruce Schneier and included in many cipher suites and encryption products. Blowfish provides a good encryption rate in software and no effective cryptanalysis of it has been found to date. 

###  AES    
The more popular and widely adopted symmetric encryption algorithm likely to be encountered nowadays is the Advanced Encryption Standard (AES). It is found at least six time faster than triple DES.
The features of AES are as follows −
<ul>
<li>Symmetric key symmetric block cipher</li>
<li>128-bit data, 128/192/256-bit keys</li>
<li>Stronger and faster than Triple-DES</li>
<li>Provide full specification and design details</li>
<li>Software implementable in C and Java</li></ul>

###  DES3
In cryptography, Triple DES (3DES or TDES), officially the Triple Data Encryption Algorithm (TDEA or Triple DEA), is a symmetric-key block cipher, which applies the DES cipher algorithm three times to each data block.


## Tf-Idf vectorizer + SVM (multi class)
     Results:
         Training set accuracy : 49 %      Validation set accuracy : 45%

## Histogram Method :
     SVM(multi class) Results:
         Training set accuracy : 100 %      Validation set accuracy : 91.6%
         
     Random Forest Classifier(multi class):
         Training set accuracy : 99.7 %      Validation set accuracy : 99.5%         
   
      
