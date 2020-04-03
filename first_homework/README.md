# 따로 쓰는 에디터가 없으신 분들은 vscode 설치해주세요
## vscode 사용시 주의사항
1. live server 확장자 설치하기
2. 한글 설정은 확장자 에서 kroean 검색하지고 microsoft에서 제공하는 확장자 설치하시면 됩니다.
3. encoding 설정을 utf-8로 해주세요

### 확장자는 좌측에 네모 4개로 이뤄진 아이콘입니다.

### encoding 설정 방법
1. 파일 -> 기본 설정 -> 설정
2. 상단의 검색창에 encoding 검색
3. encoding 설정 "utf-8"로 바꿔주기

## live server 실행 방법
1. `ctrl`+`shift`+`P` 를 누른다
2. live server 검색
3. Live Server : Open with Live Server 클릭

다음코드를 적용해서 live server를 실행해보세요

```html
<!DOCTYPE html>
<html>
    <head>
        <style>
            .box-container{
                display:flex;
            }
        </style>
    </head>
    <body>
        <div class="box-container">
            <div>hello1</div>
            <div>hello2</div>
            <div>hello3</div>
        </div>
        <div class="box-container">
            <div>hello1</div>
            <div>hello2</div>
            <div>hello3</div>
        </div>
    </body>
</html>
```

## 과제 제출 방법
반드시 **Pull Request** 를 날려주세요

과제를 제대로 완료했다면 이미지에 마우스를 가져가면 이미지가 흔들립니다.

## 참고 링크
[PR 관련] : https://wayhome25.github.io/git/2017/07/08/git-first-pull-request-story/   
[W3School] : https://www.w3schools.com/
