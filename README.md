# python

## 가상 환경 구축

1. pip 설치

    ```
    pip install virtualenv 
    ```

2. 가상 환경 생성

    python 3.10 버전으로 venv 라는 이름의 가상 환경 생성 예

    ```
    python -m virtualenv venv --python=python3.10
    ```

3. 가상 환경 활성화

    ```
    source ./venv/bin/activate
    ```

4. 가상 환경 비활성화

    ```
    deactivate
    ```

## 새로운 가상 환경에 현재 가상 환경 구성 옮기기

1. 패키지 목록 저장

    ```
    pip freeze > requirements.txt
    ```

2. 패키지 설치

    ```
    pip install -r requirements.txt
    ```