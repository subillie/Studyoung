# Studyoung

신한 해커톤 출품 프로젝트입니다.  

Studyoung은 학습 시간 측정, 스터디 그룹 시스템, 위치 기반 친구 찾기, 학습 목표 설정 및 관리 기능을 통해 학생들의 학습 효율성과 소셜 활동을 동시에 강화할 수 있습니다. 금융 혜택과 학습 관리를 결합하여, 학생들이 학습을 통해 보상을 받고, 신한은행의 금융 서비스도 자연스럽게 경험할 수 있도록 합니다.

## 👥 Team

팀명: **`Hey해지지마영`**

### Work Pages
[Google Docs](https://docs.google.com/document/d/1MFORXQ5TRO2KhZZnXdwOpIB8Bm0mYklSr0E40iUTmOI/edit?tab=t.u8u8bbapyy73)  
[Figma (Wire Frame)](https://www.figma.com/design/GrrarW92keO7xxN0aOnlwV/Hey%ED%95%B4%EC%A7%80%EC%A7%80%EB%A7%88%EC%98%81?t=UfjBYhAdrvaYJIiM-0)  
[DB ERD](https://dbdiagram.io/d/Studyoung-6891975edd90d17865715b99)  

### Frontend
<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/wynsumhi"><img src="https://avatars.githubusercontent.com/u/100817058?v=4" width="100px;" alt=""/><br /><sub><b>김현아</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/songjinhyun"><img src="https://avatars.githubusercontent.com/u/58201319?v=4" width="100px;" alt=""/><br /><sub><b>송진현</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/gyqls080813"><img src="https://avatars.githubusercontent.com/u/124768918?v=4" width="100px;" alt=""/><br /><sub><b>이민엽</b></sub></a><br /></td>
    </tr>
  </tbody>
</table>  

### Backend
<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/sanghyeom"><img src="https://avatars.githubusercontent.com/u/95522882?v=4" width="100px;" alt=""/><br /><sub><b>윤상현</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/subillie"><img src="https://avatars.githubusercontent.com/u/112736264?v=4" width="100px;" alt=""/><br /><sub><b>이수빈</b></sub></a><br /></td>
    </tr>
  </tbody>
</table>  

## Tech

### Frontend
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

### Backend
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)

### To Run
`Python 3.12` version에서 테스트되었습니다.  

가상환경 생성 및 활성화 (필요하면 실행)
```shell
python3 -m venv .venv
source .venv/bin/activate
```

필요한 패키지 설치
```shell
pip install -r requirements.txt
```

서버 실행
```shell
# 최초 실행 시에만 필요
python3 manage.py makemigrations
python3 manage.py migrate
# 서버 실행
python3 manage.py runserver
```

## Beta
