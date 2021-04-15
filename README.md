# markdown 강의

# Inline Code

python에서 `random` 패키지에서 `randint` 함수를 사용하세요.

# Python Code & Java Code

```python
name = 'World'
print(name)
```

```java
int a = 1;
float b = 2;
double c = a + b;
```

# 코드
    def sum(a, b):
      return a + b

markdown language 공부

## 차례
1. [강조](#Emphasis)
2. [리스트](#Lists)  
  i. [숫자없는리스트]
4. [테이블](#Tables)
5. [링크](#Links)

## Emphasis

이것은 한 *문장*입니다.  
이것은 다음 문장입니다.

이것은 다음 **문단**입니다.  
이것은 다음 문장입니다.

이것은 또다른 ***문단***입니다.
이 내용은 ~~취소~~해요.

## Lists

- 첫번째 아이템  
  - 서브 아이템  
    - 서서브 아이템
- 두번째 아이템
- 세번째 아이템

1. 첫번째 아이템  
   1. 서브 아이템
   2. 서브 아이템
2. 두번째 아이템
   - 서브 아이템
   - 서브 아이템
3. 세번째 아이템

| 첫번째 열 | 두번째 열 | 세번째 열 | 네번째 열 |
|---------|:--------|:-------:|-------:|
| 기본 | 왼쪽 정렬 | 가운데 | 오른쪽 정렬 |
| 아무거나 | 아무거나 | 아무거나 | 아무거나 |

## Links
구글로 가고 싶으면 [이것](https://www.google.com)을 클릭하세요.  
라이선스를 보고 싶으면 [이것](./License)을 클릭하세요.

구글 홈페이지로 가실려면 [이것][1]을 클릭하세요.  
야후 홈페이지로 가실려면 [이것][2]을 클릭하세요.  
네이버 홈페이지로 가실려면 [이것][3]을 클릭하세요.

[1]: https://www.google.com
[2]: https://www.yahoo.co.jp
[3]: https://www.naver.com

구글 홈페이지는 https://www.google.com  
구글 홈페이지는 <https://www.google.com>

강조를 사용하려면 [Emphasis 섹션](#Emphasis-is-Here)

![구글 로고][구글이미지]
[구글이미지]: www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png "구글 로고이미지"

<img
src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png" width = 100>
