## Git

# / : delimeter
# cd .. : 상위 directory
# a : 숨김 파일 활성
# ls -a : 숨김 파일 보기
# ls -l : 숨김 파일 디테일하게 보여줌
# mkdir : 디렉토리 만들기
# touch : 새로운 파일 만들기
# mv : (move) 이동
cd sample/ : 하위폴더인 sample로
mv main.js sample : main.js를 sample로 이동
mv ../test.txt . : 상위에있는 test.txt를 현재(.)로 이동
# cp : (copy)
cp server.py ./server-copy.py : server.py를 server-copy.py로 복제해서 새파일 생성
cp sample.md sample/ : sample.md를 sample 하위 폴더로 복제
cp ../server.py ./ : 상위 디렉토리에 있던 server.py를 현재 디렉토리에 복제
# rm : (remove)
rm *.py : py 확장자가 들어간 파일 다 지우기
rm sample.* : sample이 들어간 파일 다 지우기

mv old.py new.py : old.py를 new.py로 rename
mv ./new.py ./old.py = mv old.py new.py : ./ 생략
# rm -r sample/ : sample/ 디렉토리 삭제
# vim, vi : 파일 열기
normal 모드가 기본 i누르면 insert 모드
# ## : 제목 text로 표시
# - : 순서가 없는 item 나열
# ``` : command 하이라이트 처리
esc누르면 다시 normal 모드
shift + ; : command 모드
:wq : 저장하고 나가기
cat : text 라인을 취합해서 쉘에 보여줌 -> 내용 확인 가능!

