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
