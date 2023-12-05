# ML-Project-2023
Final project for ML course for 2023 M Sem

#install required libraries
pip install transformers torch

use the Ramayana dataset or use your own sanskrit text data.
Update file paths in the code to point to your dataset.
The dataset can be downlaoded from the repo. Load the text dataset and use appropriate paths.

Fine-tune the model as needed.

Install:
pip install pytesseract Pillow
pip install pytesseract Tesseract
pip install transformers

Data Cleaning:
Remove all non-devanagari characters from the dataset, like information about encoding, dates, verse tags etc.

![image](https://github.com/suryaketaraju/ML-Project-2023/assets/54495222/5c2dfabe-65c3-4adb-8fbc-e20e66ec6164)

after pre-processing our data looks like

![image](https://github.com/suryaketaraju/ML-Project-2023/assets/54495222/78685284-78d4-46fa-a3d8-467be8e06ee0)

OCR

take this image for sample

![image](https://github.com/suryaketaraju/ML-Project-2023/assets/54495222/31d63d45-5328-4db7-951c-6c162ddf4d37)

which after OCR results in a text output like

![image](https://github.com/suryaketaraju/ML-Project-2023/assets/54495222/f1a77fa6-10d2-48f1-9c0a-8b066b33741a)

 You don't particularly need to upload an image and test the model, you can also give text prompts directly to it using the variable text_prompt as given in the code.

 For e.g.
 We give the prompt:
 
![image](https://github.com/suryaketaraju/ML-Project-2023/assets/54495222/db06e562-108e-4baa-87c9-af35bddfd06c)

And the model completes this quartet of a verse into an anushtubh verse, the meter in which the valmiki ramayana is composed.

![image](https://github.com/suryaketaraju/ML-Project-2023/assets/54495222/8382f486-ee14-4186-b842-19038629242e)


Future plans:
The model can be trained further on more expansive data and taught other meters as well in sanskrit prosody.

Acknowledgments
Hugging Face: For providing the transformers library and pre-trained language models.
Prof John Smith and Prof Tokunaga Muneo for making the ramayana dataset available.
