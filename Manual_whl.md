# .whl 파일을 사용하여 Python 라이브러리를 수동으로 설치

# 1. .whl 파일 다운로드(의존파일 존재 여부 필수 체크!!)

    # 1-1. 필요한 라이브러리의 .whl 파일을 공식 사이트(PyPI 등)에서 다운로드_버전 일치여부 확인 필요

# 2. 터미널(명령 프롬프트) : CMD나 PowerShell, macOS/Linux라면 터미널을 실행 or 코드 실행 환경에서 콘솔창에 입력

    # 2-1. whl 파일이 위치한 경로 입력 : cd C:\Users\YourUsername\Downloads

    # 2-2. pip 설치 : pip install 파일명.whl 
    # ex) example_lib-1.0.0-cp39-cp39-win_amd64.whl > pip install example_lib-1.0.0-cp39-cp39-win_amd64.whl

# 3. 라이브러리 설치 확인

    # import example_lib 
    # print(example_lib.__version__)

# requirements.txt 파일 생성 > 콘솔
    
    # pip freeze > requirements.txt

# 