# 스케줄

---

# 제목1

## 제목2

### 제목3

#### 제목4

##### 제목5

###### 제목6

### BlockQuote

> This is a first blockquote
>
>> This is a second blockquote
>
> This is a first blockquote

### 목록 (LIST)
#### 1) 순서가 있는 목록
1. 목록 1
    1. 목록 1-1
    2. 목록 1-2
2. 목록 2
    1. 목록 2_1
    2. 목록 2_2
3. 목록 3
4. 목록 4

#### 2) 순서가 없는 목록
- 목록 1
    - 목록 1_1
    - 목록 1_2
- 목록 2
    - 목록 2_1
    - 목록 2_2
- 목록 3

### 표 만들기

- | (vrtical val) : 테이블 표현
- : : 정렬
- --- : 헤더와 셀 구분

|이름|주소|전화번호|
|:--:|:--:|:--:|
|홍길동|서울시|02-1234-1234|
|김펭귄|경기도|031-1234-1234|

### 코드 (code)
#### 1) 인라인 코드(inline code)
- 백틱(\`)으로 강조할 내용을 감싼다.
    repository에서 프로젝트의 설명을 부여해줄 때 `README.md`를 사용한다.

#### 2) 블럭 코드(block code)
- 백틱(\`) 3개로 html, css, java 등 코드를 작성할 때 사용한다.

    ``` java
    public static void main(String[] ages) {
        System.out.prientln("Hello java");
    }
    ```

### 글자 강조

**굵은 글씨**
_이텔릭_
~~취소선~~
__밑줄__

### 링크 (link)

[naver](https://www.naver.com/){:target="_blank"}
[link](a.txt){: target="_blank"}
다음 홈페이지 : <https://www.daum.net/>{:target="_blank"}

### 이미지 (images)
![naver](https://ssl.pstatic.net/melona/libs/1425/1425841/53c2b0e9ae2be7d850fe_20221206101103180.jpg)
![box](./images/penguin.jpg)
[![daum](./images/daum.png)](https://www.daum.net/){:target="_blank"}
