# CitRet_Public

## CitRet
Code for paper "CitRet: A Hybrid Model for Cited Text Span Retrieval for Scientific Documents"

We will soon release the full version of CitRet. Meanwhile, you can mail us on amit.pandey@research.iiit.ac.in and amitpandeyresearch@gmail.com to request access to the CitRet private repo. Please mention " ACCESS to CitRet" in subject.

-Warm Regards,
Amit Pandey

## Instructions to run the code
* Install dependencies
```
conda env create --name envname --file=environment.yml
```
* Download datasets 2018,2019 from https://github.com/WING-NUS/scisumm-corpus <br>
We downloaded 2018 dataset from https://github.com/WING-NUS/scisumm-corpus and 2019 Dataset from https://drive.google.com/file/d/1X9pZTLRx-ULZNvWPkhxL-IeDJrSRYD48/view?usp=sharing
* Run 
``` python main.py --dataset_tpye <> --dataset_path <>```
