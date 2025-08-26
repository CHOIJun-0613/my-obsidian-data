회사 업무에서 가끔 파이썬을 사용하게 되는데 가상환경을 생성할 때마다 명령어를 찾기 번거로워 블로그에 정리해둔다. 파이썬에서 가상환경을 사용하는 이유는 

# 1. 가상환경 생성

Python 3.5 버전 이후부터는 venv가 표준 라이브러리에 내장되어있기 때문에 별도 설치는 불필요하다. 가상환경을 생성하기 원하는 디렉터리로 이동하여 아래 명령어를 실행한다.

```mel
python -m venv 가상환경이름
```

명령어가 잘 실행되었다면 설정한 가상환경이름과 동일한 이름의 디렉터리가 생성된다.

# 2. 가상환경 활성화

MacOS의 경우 아래 명령어를 실행하여 가상환경을 활성화 할 수 있다.

```bash
source 가상환경이름/bin/activate
```

참고로 Windows의 경우 실행파일의 경로가 상이하다.

```bash
source 가상환경이름/Scripts/activate
```

가상환경이 실행되면 터미널 명령줄 맨 앞에 가상환경 이름이 출력된다.

[예시: 가상환경 이름을 .venv로 설정한 경우]

```crystal
(.venv) $  git status
```

# 3. 가상환경 비활성화

가상환경을 비활성화 하려면 아래 명령어를 실행한다.

```ebnf
deactive
```

# 4. 가상환경 삭제

생성한 가상환경을 삭제하려면 아래 명령어를 실행한다.

```bash
sudo rm -rf 가상환경 이름
```

            




                    

출처: [https://canaryrelease.tistory.com/62](https://canaryrelease.tistory.com/62) [release: canary:티스토리]