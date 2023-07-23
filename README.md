# opticalCharacters | OCR Library from scratch in Python 3.10
## Contributors: dorkydanny
### Lnk to Proj. [https://github.com/dorkydanny/opticalCharacters](url)
-------------------------------------------
### I - A not so quick introduction to OCR
### II - What do you need?
### III - Get the data
### IV - What do we do with the data?
### V - Handy tools
### V - In Conclusion
--------------------------------------------
# I - A not so quick introduction to OCR
Optical Character Recogntion or more commonly referred to as OCR is effectively the process (in a programming point of view) of having a massive set of chracters with tags set on them (further detail in data augmentation) to train an "AI" to be able to find rules and patterns inside of those characters to be able to perform effectively to be able to tag a letter with the right character. That is the end goal.   
#### (i - Data Augmentation)  
Data Augmentation  - the process of, well, (simply put) processing data. Augmentation refers to obtaining a large set of characters that humans have been trained to recognize throughout their whole life, and help machines understand them by writing the right answer in (the right answer in this case would be what we are hoping the machine is eventually going to give us as an output). In this case for data augmentation we will be using popular software (Albumentations). It looks something like this:  
![image](https://github.com/dorkydanny/opticalCharacters/assets/83188206/e1d1d673-051f-4873-9d7a-3dc8954bf764)

#### (ii - Training).  
![image](https://github.com/dorkydanny/opticalCharacters/assets/83188206/49c705fc-4337-4891-9fc3-29a5606f283e)

(iii -  Asking for Answers).  
(iv - Loss).  
