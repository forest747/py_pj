# first
my first flask app source

배포 관련 사항
deploy.json : 도메인, 아이피등 정보
              형식이 JSON 이라서 주석 불가
wsgi.py     : enrty 파일, 서버구동시 시작점
fabfile.py  : 페브릭 작업 내용 기술
fabfile_comment.py  : 주석 버전
requirements.txt    :  서버구동시 필요한 모듈을 기술(버전 포함) 개발할때 썻던 버전 명시.

# 서버 로그 확인
접속로그 (파이썬 로그)
> tail -f /var/log/apache2/access.log
애러로그 (500에러 발생시, internal server error)
> tail -f /var/log/apache2/error.log
