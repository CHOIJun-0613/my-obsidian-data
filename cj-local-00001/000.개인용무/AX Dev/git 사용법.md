
- GIt은 리누스 토발즈에 의해 개발된 분산형 파일 버전 관리 시스템을 말함 
- GitHub는 Git을 웹호스팅을 통해 관리할 수 있게 해주는 무료 웹사이트

![](https://blog.kakaocdn.net/dna/th4gx/btq8f9uY82N/AAAAAAAAAAAAAAAAAAAAAOx6TMwnhV3QOm4K10SXMYMWgGA9C2HFZjWpPDd1TU3o/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=c4W0uDDBxNoeseqOvpTzNcb0HNY%3D)

git의 아키텍처

gitbash를 통해 윈도우 환경에 git을 사용할 수 있는 환경 구성 가능

1. PC의 윈도우 Git 레파지토리 구축을 위해 GitBash 설치([https://gitforwindows.org](https://gitforwindows.org))

- 윈도우에 Linux/Unix의 Bash Shell 기반 Command Line 명령어 입력 환경을 제공
- Git Command 지원
- GUI기반 레파지토리 관리 툴 제공

![](https://blog.kakaocdn.net/dna/nstYc/btq8iwJ5OxS/AAAAAAAAAAAAAAAAAAAAAFNyu5Qb7ah-iAokLCfo44KBHobKWvoLLvAaIe14Dakm/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=9OMq%2F5vS9fueafO7itx9b3W%2F4ys%3D)

2. GitHub에 New Repository 생성 

- [https://github.com](https://github.com) 회원가입
- 신규 레포지토리 생성 

![](https://blog.kakaocdn.net/dna/d3suCV/btq8hlWlzjF/AAAAAAAAAAAAAAAAAAAAAGY0GKW69FdHXb5HdPkL5SevIbqdSlLvRuAvN3eebHn_/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=yDnGTKNAjZGZFuVOMLoU1o6EUH0%3D)

3) GitHub 레파지토리 옵션 설정

- Repository Name: 사용할 레파지토리의 이름을 기입(여기서는 ‘hello_git’ 을 사용)
- Public : 레파지토리의 사용 범위 선택(여기서는 ‘Public’으로 선택 ) 
- Public은 모든 사용자에게 레파지토리를 오픈하는 형태 
- 단, 업로드의 경우 Public 이라도 계정을 통해 인증된 사용자만 등록 가능
- Private를 선택한 경우 계정 당사자 이외에는 접근 불가

![](https://blog.kakaocdn.net/dna/Z6vbU/btq8bqSffFo/AAAAAAAAAAAAAAAAAAAAANf0ejypL0UOX6pOZSA86vjDETzFVZIVnHwptSTNvqxJ/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=QnpIzOFHnyklH3U8rehv8eIZsz0%3D)

- Create repository : 모든 설정이 완료되면 ‘Create repository’를 선택해 레파지토리를 생성

![](https://blog.kakaocdn.net/dna/bhkOqW/btq8a1ZuDAj/AAAAAAAAAAAAAAAAAAAAAOTEEgd5FYC8S-O4Lj8XkvrF92jUrfwh8vghpbf7rBOy/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=JFAVMb5pwN0HqTXQ%2BZ3acgD%2BQmQ%3D)

- 레파지토리 생성을 통해 위 페이지 나오는 거 확인 

3. 로컬 Git과 웹 GitHub 연동

- 1) PC상에 Git Repository위치로 쓸 디렉토리를 선택해 레파지토리 생성   
    Ex) C:\java-msa\git-repository
- Git init 명령어 수행
- 위에서 만든 로컬 레파지토리 디렉토리로 Bash shell을 실행해 이동

![](https://blog.kakaocdn.net/dna/bV3yrr/btq8gnG6SEF/AAAAAAAAAAAAAAAAAAAAAG-wuhJXWbk8Sk9XkofRYiySlvc3H_-wRLLjkKlzr9kN/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=YVqcx4Kd9638RXiyhZu0Rny16OE%3D)

- 이 예제에서는 C:\msa-java\hello_git을 레파지토리로 사용 
- bash에서는 cd\ 명령어를 통해 원하는 디렉토리 접근 가능

![](https://blog.kakaocdn.net/dna/z4NCF/btq8gnAlt6L/AAAAAAAAAAAAAAAAAAAAANDSZ2Lwu0hC5GVbwGl1KmTszRrIIlDNPUrmRCICnCJb/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=jq1C5XGkDqa0NLF5t8VzY%2F5OjUE%3D)

- git init 명령어 수행을 통해 git을 초기화

![](https://blog.kakaocdn.net/dna/bvXMAy/btq8aDR4XVA/AAAAAAAAAAAAAAAAAAAAAJ8N8IsFSYcXgIvckt3_LDkLWzpHP7cbB2tj2phQp8WH/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=32NgPNnzsolt1uu8fH9kSrK1P0k%3D)

- git remote add를 통해 hello_git 을 리모트에 연동

![](https://blog.kakaocdn.net/dna/bkFsXh/btq8ewY4r2r/AAAAAAAAAAAAAAAAAAAAAKJ3LAlzflpT9ok_Mdb2Z2xG18vXJKqkXbYRIX_LV10R/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=q5wUHZblTts1IBKrlK25d6DvN7g%3D)

 사용되는 코멘드는 ‘git remote add origin [아까만든 git URL, 여기서는 hello_git + .git]’

url을 잘 모를 때는 인터넷 git hub의 hello_git의 명령어 참조 페이지를 참고 할 것

![](https://blog.kakaocdn.net/dna/pG163/btq8hqiVOSh/AAAAAAAAAAAAAAAAAAAAAB8KDauIBu3lSESEDgY8CWCO6FUMPbIcJsrmAmhu1wOx/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=kCsSz5CIEhVseovPyVYZNZW1f5E%3D)

명령어가 정상 수행되면 디렉토리에 .git이 생성되었으며 다양한 관련 파일이 생성된 걸 볼 수 있음

![](https://blog.kakaocdn.net/dna/b3H1vo/btq8dum7MnG/AAAAAAAAAAAAAAAAAAAAAAGnTZfoHpHZBeVyMhNac0wncdBfyaB2lDyjgPlFuMBY/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=tp9ou9tNWI7Oo5sUm02RoCyFKfs%3D)

4. Pull과 Push

- push : 로컬 Git Repository의 데이터를 연결된 GitHub로 집어 넣는 작업
    
    - git status  로컬데이터와 git레파지토리 싱크 체크
    - git add .  로컬데이터와 git레파지토리 틀린점을 트래킹해서 싱크
    - git commit –m “message”  커밋시 커밋의 이유(메시지)를 다는 명령어
    - git push origin +master 
    
- pull : 리모트 Git Repository에서 데이터를 가져오는 작업
    
    - **일반적으로 Push전에 Pull을 진행,** **이는 실수로 Remote의 GitHub를 Overwrite 하지 않도록 하기 위함**
    

5. Push Test

- 앞서 만들었던 레파지토리(Ex: C:\java-msa\git-repository)로 이동해 임의의 텍스트 파일 하나를 만들도록 한다.
- 여기서는 “Hello Git Test.txt”라는 파일을 만들고 내용으로는 “This is hello git test message”라고 입력해 두도록 합니다.
- 탐색기로 생성된 git 레파지토리로 옮겨 git-bash를 시작하도록 합니다.

![](https://blog.kakaocdn.net/dna/YiWls/btq8ftOz6dZ/AAAAAAAAAAAAAAAAAAAAADzqW2SodqZz3opVavVQfTNvL2uQx1ThB72yGqeHTuCK/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=2zLlQXu1L8ko3fI%2FyLtGunu%2BjKw%3D)

- git status 명령어 수행를 통해 로컬 레파지토리와 github 레파지토리를 비교

![](https://blog.kakaocdn.net/dna/cpDy85/btq8gmVJQ47/AAAAAAAAAAAAAAAAAAAAAEG4C_HxNAttynlyx8k-qEL2xRs1TcWEZJbuEax4MIaa/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=6YFRyNvNGP92QFZDoSHyMYxn3nQ%3D)

- git add . 명령어를 통해 github에 파일 트래킹, 여기서 "."은 모든 파일을 의미 합니다.
- git commit –m “My first git file“ , 여기서 따옴표 안에는 커밋을 위한 메시지를 입력하도록 합니다.

![](https://blog.kakaocdn.net/dna/bcTIsI/btq8bqSffH4/AAAAAAAAAAAAAAAAAAAAAK0VjmtGZIjiuwej-4QMy63djkleC3nOUx6cH37qzqJ6/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=%2FkxXSBQkJ7sqRWrIDi9B0s8DY10%3D)

- 여기서 위와 같이 에러가 나온다면 로컬 git에 대한 환경 설정이 안되어 있다는 메시지 입니다.

![](https://blog.kakaocdn.net/dna/MbswF/btq8c0s35KR/AAAAAAAAAAAAAAAAAAAAACzIab_3Ck2ZVrWlJYLZ9NI9LyzDv0iXDBk4KJthjCnX/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=Yn8%2BzWSe%2B6NMhQDDadqbhLpoFWA%3D)

- 환경 설정 명령어(콘솔 메시지 참조)를 통해 git에 가입한 email addr과 사용자 명을 입력하도록 합니다.

![](https://blog.kakaocdn.net/dna/brsunW/btq8duAFPjo/AAAAAAAAAAAAAAAAAAAAAA4a9G5TA_PaOuGl_2k16OQL0c88khD4Tn__CzEwBLMY/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=PJIJ4foG1o%2B41H%2BSVVThM2JBrUU%3D)

- 모두 끝났으면 위와 같이 다시 한번 git commit –m “message”를 입력하도록 합니다.
- 여기서는 My First git file이라는 메시지를 입력 했습니다.

![](https://blog.kakaocdn.net/dna/oGpHE/btq8iwDkGhK/AAAAAAAAAAAAAAAAAAAAANU3ym0EtMQTBHs3tP7CuYt03S3yekPQzOp2ioG2TEEX/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=6zythBK3w2TWiZKvAzhAu2jTzu0%3D)

- git push origin master 입력
- 실제 데이터 push를 위해 git push origin master 명령어를 입력 하도록 합니다.
- 이때 사용자 이메일과 git hub에 가입된 패스워드를 입력해야 합니다.
- 앞서 설명했듯이 public github라 하더라도 데이터 입력을 위해서는 허가된 사용자만 가능합니다.
- github 홈페이지에서 업로드 파일 확인

![](https://blog.kakaocdn.net/dna/7QFUw/btq8b1LsPRy/AAAAAAAAAAAAAAAAAAAAAL8hAm_BRrVapS48miR6u0kFuk8e1_-fA9jBWknGjQVV/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=FjGIYkrgfjEAsyx0KjM%2Bcp7vtlo%3D)

4)Pull Test

- Pull 즉, remote github에 등록되어 있는 최신의 파일을 local이 레파지토리로 복사하는 작업
- 테스트를 위해 원격 github의 실습용 레파지토리인 hello_git에 가지고 있는 소스 파일(하위 디렉토리를 가지고 있어도 상관없다.)을 올려 둡니다.

![](https://blog.kakaocdn.net/dna/E8gsA/btq8fXBS9NG/AAAAAAAAAAAAAAAAAAAAAA0NnXqP5o9NFw63YfzKPt3e9DcsWqm0_R-XufV6l6w1/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=ou0LfQ9LsqL86eVsG%2BQarNc1gjY%3D)

- github는 drag&drop을 지원하기 때문에 업로드를 원하는 파일을 선택 한 후 아래의 그림에 있는 Drag files here to add them to your repository에 파일(혹은 디렉토리)을 끌어다 놓도록 합니다.

![](https://blog.kakaocdn.net/dna/bFb5LJ/btq8c0GBvmb/AAAAAAAAAAAAAAAAAAAAALNsLO0CJl-2ek5oBWe4XHlBCb2bztyYLYo_dQDmk5G6/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=Uw3u2c6MSRef1JN3M4c4JVNgHCg%3D)

-  정상적으로 파일 업로드가 완료되면 아래의 그림과 같이 업로든 파일의 리스트가 보인다.

![](https://blog.kakaocdn.net/dna/ccsTIK/btq8ftHPT5o/AAAAAAAAAAAAAAAAAAAAAD-bj957FDGZNCch9v8R0Lvuxs-0golwtdyvgCij8yd1/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=tKbCXDgfv2%2F4iGLGNj6%2FP6KOZgE%3D)

- 이제 로컬의 git repository상에서 git pull origin master 명령어를 통해 remote github에 있는 데이터를 가져옵니다.

![](https://blog.kakaocdn.net/dna/AcWCi/btq8aDqYTna/AAAAAAAAAAAAAAAAAAAAAFMg4litgbb5FkFbTtcOqllkhbtrgYJrgmSwB11lp3yl/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=vQmuJ4ZCbfy6erCpIlYwsCnZz%2B4%3D)

- 가져온 파일들을 확인 해 볼 수 있습니다.

![](https://blog.kakaocdn.net/dna/cADAYJ/btq8eIxD3lD/AAAAAAAAAAAAAAAAAAAAAKTGeRyuTzrCPKaoo81g_f7cNR3KkFfthPh4Z3a9tuZ3/img.png?credential=yqXZFxpELC7KVnFOS48ylbz2pIh7yKj8&expires=1756652399&allow_ip=&allow_referer=&signature=U%2F8rGirBL1slVNoAETHPLndSPPI%3D)

5) github.com에 들어가 변경된 파일을 확인해 봅니다.

끝 ~

출처: [https://sharplee7.tistory.com/3](https://sharplee7.tistory.com/3) [Deok's Architecture Blog:티스토리]