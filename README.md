# my_blog

이름:
Jiwon Shin

money money


# 제목 1 (h1)
문서를 작성한 후 아래 단축키를 누르면 *반영된 결과*를 볼 수 ~~있습니다~~.있다.


**Preview 단축키 : Ctrl + Shift + K**  

## 제목 2 (h2)

글 중간에 목록을 삽입하고 싶은 경우  

- 아이템 1
- 아이템 2
   - 서브 아이템 1  
   - 서브 아이템 2


순서가 있는 목록을 삽입할 수 있습니다.  

1. R 언어 패키지  
    1. ggplot  
    1. Dplyr  
1.  파이썬 패키지  
    1. 넘파이  
    1. 판다스

## 제목 3 (h3)
문의사항은 [슬기로운 통계생활](https://staple.com)로 문의주세요!  


![슬통로고](https://statisticsplaybook.com/wp-content/uploads/2023/09/%EC%8A%AC%ED%86%B5%EB%A1%9C%EA%B3%A0%EB%94%94%EC%9E%90%EC%9D%B8-%ED%88%AC%EB%AA%85512x512.webp)


![컴퓨터에 저장된 그림](./슬통로고디자인.webp)



### 표 삽입

| 이름  | 나이 | 직업 |
|------|----|-------|
| 홍길동 | 25 | 데이터 분석가 |
| 이몽룡 | 30 | 개발자  |


### 수식 입력

문장 안에 들어가는 수식은 달러 기호 한개를 사용합니다.
이렇게 $E=mc^2$ 말이죠!

만약, 수식만 따로 문단을 만들어서 보여주고 싶은 경우는 달러 기호 2개를 사용합니다.

$$
E=mc^2
$$

이렇게 말이죠!

$$
\begin{aligned}
    a &= b + c \\ 
      &= d + e + f
\end{aligned}
$$

* `\\` 기호는 줄바꿈을 의미
* `&` 기호는 정렬 기준을 의미

## Quarto의 존재 이유

파이썬 코드 청크를 삽입할 수 있다.

단축키 : `Ctrl + Shift + I`
```{python}
import numpy as np

a = np.arange(10)
a
```