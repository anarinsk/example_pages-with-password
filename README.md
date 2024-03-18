# example_pages-with-password

제공되는 페이지 (암호는 0000)
https://anarinsk.github.io/example_pages-with-password/billboard.html

## First Thing First 

### gh-pages 브랜치 만들기 

터미널에서 아래와 같이 실행한다. 

 ```bash 
 $ quarto publish gh-pages
 ```

gh 설정을 통해서 로그인이 구현되어 있어야 한다. gh는 github를 활용하기 위한 터미널 앱이다. 링크를 참고하자. 

### github pages 설정 

- `Build and deployment`  
    - `Source` > "Deploy from branch" 선택
- 아래 Branch에서 gh-pages 브랜치를 선택하고 저장한다.

### Github Actions를 제어 

`.github/workflows` 폴더에 yml 파일들을 수정한다. 현재 이 페이지의 경우 

- `0_publish.yml`
- `1_staticrypt.yml`

첫번째 파일의 실행이 완료된 이후 두 번째 파일이 실행되는 구조를 지니고 있다. 






