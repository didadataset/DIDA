![Swedish historical handwritten document](https://ars.els-cdn.com/content/image/1-s2.0-S2214579620300502-gr001.jpg)

## DIDA: The largest historical handwritten digit dataset with 250k digits
DIDA is a new image-based historical handwritten digit dataset and collected from the Swedish historical handwritten document images between the year 1800 and 1940. It is the largest historical handwritten digit dataset which is introduced to the Optical Character Recognition (OCR) community to help the researchers to test their optical handwritten character recognition methods. To generate DIDA, 250,000 single digits and 200,000 multi-digits are cropped from 75,000 different document images. The dataset has multiple unique characteristics as explained below:

* Degradation: The poor quality of the used papers and inks in the nineteenth centuries, age of documents, and distortions influence digits in DIDA dataset. These issues simply result in multiple degradation and artifacts. For instance age of documents causes deterioration of digits (i.e.~faint). Moreover, other artefacts in the document images are background variation, show-through, bleed-through, and smear. Consequently, the CARDIS dataset is exposed to many different inter- and intra-class variations.
* Handwriting styles: In the recorded documents, the digits were written in copperplate, cursive, and Gothic styles by different priests using various types of ink, nib, and dip pen, which result in different appearances. Moreover, in the documents the same class digits appeare with different sizes thus, the shapes can be diverse. Hence, in DIDA dataset, the digits appear in various writing styles, sizes, directions, widths, and arrangements. These variations in handwriting patterns due to individual writing style and materials used to write the texts generate endless inter-class variations.

The DIDA single digits dataset has 250,000 handwritten digit samples with 10 different classes from 0 to 9, and each class contains 20,000-25,000 single digit images. To the best of our knowledge, this dataset is the largest one to present historical handwritten single digit samples in RGB color space with the original sizes and appearances (a). This dataset is in contrast with the existing publicly available handwritten digit datasets (e.g. MNIST (b)), where the digit images are size-normalized, denoised and cleaned.

![DIDA vs MNIST](https://ars.els-cdn.com/content/image/1-s2.0-S2214579620300502-gr004.jpg)

* [single digit dataset 10K](https://drive.google.com/file/d/1d-U-lxIoS5QuPEYPvHA2-Bm4pULsTb06/view?usp=sharing)
* [single digit dataset 70K](https://drive.google.com/file/d/1WOlgL8itWZ0bTelgQcORzltnaFR2vkQy/view?usp=sharing)
* [single digit dataset 250K](https://drive.google.com/file/d/1J-NZFBdxqUQuY2mu3aBexhfiY6WUFlCn/view?ts=60f97e6c) 
* [string digit dataset](https://github.com/didadataset/dida) [This dataset will be available within 1 month]

## If you use any of these datasets, please cite:
#### Reference:

* Huseyin Kusetogullari, Amir Yavariabdi, Johan Hall, Niklas Lavesson, "DIGITNET: A Deep Handwritten Digit Detection and Recognition Method Using a New Historical                  Handwritten Digit Dataset", Big Data Research, 2020, DOI: [10.1016/j.bdr.2020.100182](https://doi.org/10.1016/j.bdr.2020.100182).
* Huseyin Kusetogullari, Amir Yavariabdi, Johan Hall, Niklas Lavesson, DIDA: The largest historical handwritten digit dataset with 250k digits, June 2021. Accessed on: June 13,        2021. Available: [https://github.com/didadataset/DIDA/](https://github.com/didadataset/DIDA/). 

#### BibTeX:
* @article{Kusetogullari2020DIDA,  
           title={DIGITNET: A Deep Handwritten Digit Detection and Recognition Method Using a New Historical Handwritten Digit Dataset},  
           author={Huseyin Kusetogullari, Amir Yavariabdi, Johan Hall, Niklas Lavesson},  
           journal={Big Data Research},  
           year={2020}  
           }
* @misc{DIDA2020,  
       author = {Huseyin Kusetogullari, Amir Yavariabdi, Johan Hall, Niklas Lavesson},    
       title = {DIDA: The largest historical handwritten digit dataset with 250k digits},    
       howpublished = {\url{https://github.com/didadataset/DIDA/}},  
       note = {Accessed: 2021-06-13}  
       }
#### News:
* 08/2021: This work was featured as the project of the month in [Computer Vision News](https://www.rsipvision.com/ComputerVisionNews-2021August/28/).
