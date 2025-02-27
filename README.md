## 🤔 나름 쓸모있는 코드들

<br/><br/>

### lib 버전관리 - .whl

<br/>

1. 내 환경과 동일한 lib.whl 파일 생성 (없을 경우 공식 사이트(PyPI) 에서 다운로드)
```python
mkdir wheels && pip wheel -r requirements.txt --wheel-dir wheels
```

2. cmd에 whl 파일이 위치한 경로 입력
```python
cd C:\Users\YourUsername\Downloads
```

3. pip 설치 : pip install 파일명.whl
```python
pip install 파일경로.whl
```

<br/><br/>

### lib 버전관리 - requirements.txt

<br/>

1. 현재 내 라이브러리와 같은 lib를 담은 requrements.txt 생성
```python
pip list --format=freeze > requirements.txt
```

2. requrements.txt 다운로드
```python
pip install -r requirements.txt
```
















































