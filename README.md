# NaverTV_Downloader
youtube-dl 기반 네이버TV 영상 다운로더   

## Requirements
```
$ pip install youtube_dl
$ pip install requests
```
## Usage
```
$ python naverTV_download.py file_name.txt resolution
```
- file_name.txt : url, 저장할 이름이 저장된 txt파일
- resolution : 저장할 해상도(144, 360, 480, 720, 1080)

## txt file format
url1,save_file_name1
url2,save_file_name2
...

예시
```
https://tv.naver.com/v/12204239,T1 vs DWG 1세트
https://tv.naver.com/v/12204239,T1 vs DWG 2세트
```

## Output
Output File: save_file_name1.mp4, save_file_name2.mp4, ...

## Cautions
 - 파일 이름 중복될 시 오류발생
 - csv파일 연동 및 텍스트파일 형식 바꾸고 싶으신 분들은 요청해주세요.

## (2020.07.23 21:35) 주피터 노트북에서 쓸 수 있도록 코드 수정 후 ipynb 파일로 업데이트
- 종명님께서 올려주신 코드를 주피터 노트북에서 바로 쓰려니까 잘 안되서 주피터 노트북에서 돌아가게끔
수정 후 그에 따른 ipynb 파일을 올렸습니다. 주피터 노트북 쓰시는 분들은 참고하세요.
- 실행 후 '텍스트 파일 이름'과 '화질'을 입력하면 다운로드가 시작됩니다.
