# 이것은 문서입니다.
## 소제목
### 소소제목
#### 소소소소제목
##### 소소소소소제목
###### 소소소소소소제목
- 리스트
헤딩은 문서의 제목이나 소제목을 나타냄(h1~h6) 문자크기 사용X

리스트는 1. 2. 3. , * , -
1. 첫번째
* 안녕
- 바보

코드블럭 ` ` 한줄 블럭
 ``` ``` 여러줄 코드블럭
```python
import time 
print('안녕')
```

[] 안에 링크이름 밖은 url
[google](https://www.google.com)
![이름](경로path)

일반
**뚱뚱**
*기울기*
~~취소선~~

수?
---

---
수
***

수
___
수평선

>인용
>>인용안인용
>>>인용안인용안인용
>>>>오?
>>>>>오오?
>>>>>>?
>>>>>>>?
>>>>>>>>?
>>>>>>>>>?
>>>>>>>>>>?

노션에서는 | 가 인용선

| 표1 | 표2|응
|-|-|-
|맞냐 | 맞아?| ;;
|이게표야?|표냐고!?|???????


노션에서는 /tabel 쓰면됨


1. 리스트
2. 리스트
    1. 리스트
    2. 리스트
        1. 리스트
        2. 리스트
        
```
dd

```
`dd`
` `


Git은 `분산 버전 관리 시스템`
-
코드개발의 히스토리(여러버전들)관리하는 도구
개발되어온 과정을 파악가능
이전 버전과의 변경 사항 비교 및 분석 가능
Git은 변경사항만 기억함.
ex) x = a+ b+c 로 3번 저장되었다면
git1 은 a git2는 b git3(최종버전x) 는 c만기억
Repository 는 디렉토리 버전 관리 저장소
git init 명령어로 로컬 저장소를 생성 선언
.git 디렉토리가 생기면 이 디렉토리 안에 도구다있!

commit은 현재 변경사항을 특정버전으로 남긴다.
최종commit은 최종버전을 말함.

워킹디렉토리 : 내가 실제로 작업하는 디렉토리

스테이징 에어리어 : commit으로 남기고싶은 특정버전이 잠깐 관리되는 공간

Repository : commit들이 저장되는 곳



***
git 명령어(터미널)
git add 이름.확장자 파일을 관리시작함
git add를 통해 스테이징 에어리어에 1차기록됨
git commit 을 통해 스테이징 에어리어에 있는 애들을 하나로 합치기 가능.
git status 는 git의 상태보기
 git config --global user.email "you@example.com" 로 git hub에 내 e메일 등록

 git config --global user.name "Your Name" 로
 git hub 이름 등록

 git log 는 커밋한 git 목록

cd ~ 는 ~(기본설정)으로 돌아가기
cd는 한단계 전 폴더로 돌아가기
ls는 현재 폴더내 폴더와 파일목록보기
ls -al 은 숨김파일까지 포함해서 목록보기
cd {경로} 는 경로위치로 이동
cd .. 은 상위폴더로 이동
mkdir {이름} 은 폴더생성
touch {이름} 은 파일 생성
rm {이름} 삭제
rm -r {이름} 폴더삭제
clear 눈에보이는 텍스트 모두 삭제
pwd 현재 경로 위치 확인
start {이름} 은 열기!

***
##  로컬 저장소에 연결하는 방법
1. git remote add origin github주소
    git push origin master 로 github에 업로드
    git remote remove origin 연결해제
    git pull
    git add.
    git push

    
2. git clone 깃허브저장소주소
    이미 저장소가 등록된 폴더내에서하면안됨
    Cloning into 'themaitreya'...
    
    remote: Enumerating objects: 3, done.
    remote: Counting objects: 100% (3/3), done.
    remote: Compressing objects: 100% (3/3), done.
    remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
    Receiving objects: 100% (3/3), 11.42 KiB | 11.42 MiB/s, done.


***
[git 꾸미기](https://pages.github.com)


___



$x^2 + x_1 , E = mc^2 , 2\frac{2}{3} $
$\alpha \beta \gamma \psi \Psi  a b c$ 
$ \int_a^b f(x)dx $

$\sum_{n=2}^{bd}c$

$\sqrt 3 $

$
f(x) = x^2\\
g(x) = \frac{1}{x}\\
F(x) = \int^a_b \frac{1}{3}x^3
$


이거야 $
[
\begin{matrix}
1 &0&2\\
2 &1&32
\end{matrix}
]
$  알겠냐

$f(x) = $
$\sqrt[y]{x} $

$\cos_{x}^{y} \qquad  \tan_{x}^{y} \quad\arctan{x}$

$a\:b\;c\,d$
$a \hspace{3mm} b$
$a~b$
$\sim \verb|~| $

$\frac\lim{x\rightarrow\infty }{x}$






