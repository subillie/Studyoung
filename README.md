# Studyoung

[1. Team](#team)  
[2. Result](#result)  
[3. Commit Convention](#commit-convention)  

## Team

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

### Tech Stack

#### Frontend
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

#### Backend
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)


## Result

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

## Commit Convention
|Tag Name|Description|
|:---:|:---:|
|**Feat**|새로운 기능을 추가|
|**Fix**|버그 수정|
|Design|CSS 등 사용자 UI 디자인 변경|
|!BREAKING CHANGE|커다란 API 변경의 경우|
|!HOTFIX|급하게 치명적인 버그를 고쳐야하는 경우|
|Refactor|코드 리팩토링|
|Docs|코드 외 문서 수정|
|Test|테스트 코드, 리펙토링 테스트 코드 관련 작업|
|**Chore**|코드 변경 없음(파일/폴더명 수정, 파일 삭제, 주석 추가/변경 등)|
