# Python 설정

3.9.19를 설치해서 사용한다.
```bash
$ brew update 
$ brew install pyenv
$ pyenv install 3.9.19
$ pyenv local 3.9.19
$ python --version # (optional) check version.
$ pip install -r requirements.txt
```

# 패키지 업데이트
```bash
$ pip install -U [package name]
$ pip freeze > requirements.txt
```
