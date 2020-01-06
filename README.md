# **git-test**



1. **$ git clone '깃허브 주소'.git**

   원격 서버(github)에 있는 저장소를 로컬에 복사해옴.

   eg) $ git clone https://github.com/oreoTaste/git-test.git

   

2. **$ git add .** 

   현재상태를 on-stage 상태로 만듦

   

3. **$ git commit -m "문구"**

   on-stage된 작업에 대해 확정 (commit작업)

   

4. **$ git push origin master**

   확정된 작업를 원격저장소에 업로드

   

5. **$ git tag '버전' '커밋식별자' "문구"**

   eg) $ git tag v0.0.1 12b55f9 -m "test"

   

6. **$ git push --tag**

   모든 태그를 서버에 등록함.

