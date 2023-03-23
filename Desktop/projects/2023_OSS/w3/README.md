# 2023_OSS
   ## 2023_OSS 수업
   ### 이미지
   ![kau_image](/Users/jjeongee/Desktop/projects/2023_OSS/w3/kau_mark.png)
   ### 3주차 git 
    [mdfile_link](/Users/jjeongee/Desktop/projects/2023_OSS/w3/README.md)
    ### LMS 링크
    [lms_link](https://lms.kau.ac.kr/)
    ### ProGit 링크
    [gitbook_link](https://git-scm.com/book/ko/v2)
    ### 주요 git 명령어
    - add: 파일을 추적 대상으로 포함시킬때, 또는 커밋 대상으로 포함시킬
   >	> - ex) git add
    ```
#!/usr/bin/env bash
echo "----------"
echo "name :"
echo "박노헌"
echo

echo "----------"
echo "student id :"
echo "202321018"

file_path=`find /home/kau2/ -name w2_homework.txt 2> /dev/null`
echo "----------"
echo
echo "file path :"
echo $file_path
echo

line_num=`wc -l $file_path | cut -c 1 -`
echo "----------"
echo "line number :"
echo $line_num
echo

echo "----------"
echo "lask line :"
tail -n 1 $file_path
```
#마크다운
## 목록
### 번호 있는 목록 : 내림차순 정렬
1. first
2. second
3. third

### 번호 없는 목록 : *,-,+
- first
- second
- third

***
-red
>	>- green
>	>	>- blue

## 강조
*single asterisks*
_single underscores_
 **double asterisks**
 __double underscores__
 ~~cancelline~~

    
