# 3주차 git

## 이미지
![한국항공대학교 로고](https://user-images.githubusercontent.com/116951160/227158337-6db80558-2711-4156-bc57-3a2dc194d308.jpeg)

## 링크
[LMS](https://lms.kau.ac.kr/login.php)

## ProGit 링크
[ProGit](http://www.oss.kr/oss_guide/show/2c619df7-40d6-43de-af7a-2b0db6c16538)

## git 명령어 정리
- add: 파일을 추적 대상으로 포함시킬 때, 또는 커밋 대상으로 포함시킬 때 사용
  - 예) git add   
- commit: 파일에 대한 정보를 파일에 직접 들어가지 않고 알 수 있게
  - 예) git commit -m "의미있는 메시지"   
- branch: main 말고 다른 저장소
  - 예) git branch branch-name   

***
# 마크다운
## 목록

### 번호 있는 목록: 내림차순 정렬

1. 첫번째
3. 세번째
2. 두번째

***

- 빨강
  - 녹색
    - 파랑

### 강조

*single asterisks*   
_single underscores_   
**double asterisks**   
__double underscores__   
~~cancelline~~   

***
# 2주차 숙제
<pre><code>
#!/bin/bash
enter=----------
echo $enter
echo name :
echo 이준희
echo

echo $enter
echo student id:
echo 2021125051
echo

echo $enter
echo file path :
loc=$(find /home/kau2 -name "w2_homework.txt" 2> /dev/null)
find $loc
echo

linenumber=$(wc -l $loc)
echo $enter
echo line number :
echo $linenumber | cut -d ' ' -f 1
echo

echo $enter
echo last line :
echo $(tail -n 1 $loc)
echo
</code></pre>
