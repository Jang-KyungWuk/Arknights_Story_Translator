# Arknights_Story_Translator

This repository has 1 ipynb file, 1 md file and 1 folder with test results

> 1. test_result
>> tr1. arknights_2020-08-25-22-05-12-tr.txt\
>> tr2. scene 1.jpg\
>> tr3. scene 2.jpg\
>> tr4. scene 3.jpg\
>> tr5. scene 4.jpg\
>> tr6. scene 5.jpg\
>> tr7. scene 6.jpg\
>> tr8. scene 7.jpg
> 2. Arknights Story Translator.ipynb
> 3. README.md

## test_result

This folder contains result of test trial\
sample video for testing was [RI-3 before operation story video](https://drive.google.com/file/d/1Ox_66tuYEsFA5C9Eh9oAad4vf1d9XjKe/view?usp=sharing)

이 폴더에는 테스트의 결과물들을 담고 있습니다.\
테스트를 위해 사용된 샘플 영상은 [RI-3 작전전 스토리 영상](https://drive.google.com/file/d/1Ox_66tuYEsFA5C9Eh9oAad4vf1d9XjKe/view?usp=sharing)입니다.

> ### arknights_2020-08-25-22-05-12-tr.txt
> txt file contains translation result\
> 번역 결과를 저장한 txt 파일입니다.
>
> ### scene 1.jpg ~ scene 7.jpg
> jpg image files with 10 dialogues each.\
> 대사를 10개씩 저장한 jpg 이미지 파일입니다.

## Arknights Story Translator.ipynb

This ipynb file was written in python 3 and made with Google Colaboratory\
When story video is given, program check whether given frame has completed dialogue, and save 10 dialogue images by jpg file.\
Then using Google cloud vision API, recognize chinese in jpg files and translate them by Google translation API.\
Save the chinese and translated korean texts as txt file.

이 ipynb 파일은 python 3로 Google Colaboratory 환경에서 작성되었습니다.\
스토리 동영상이 주어졌을 때 프로그램은 프레임에 완성된 대사가 있는지 체크하고 대사를 10개 단위로 묶어서 jpg 파일로 저장합니다.\
그 뒤 Google cloud vision API를 통해 jpg 파일의 중문 문자를 인식하고 이를 Google translation API로 번역합니다.\
중문과 번역된 한글을 txt 파일로 저장합니다.

## README.md

This file is README.md

지금 이 파일이 README.md 입니다.


