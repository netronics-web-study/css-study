# 사용순서

1. 해당 repository를 자신의 local vscode에 가져옵니다 (git clone)

2. git branch 개인브랜치이름 명령어를 통해 개인 branch를 생성합니다.

3. 해당 branch에서 작업후 git add . -> git commit -m "작업내용" -> git push 를 통해 branch를 업데이트합니다.
4. github 홈페이지에서 pull-requests 기능으로 자신의 branch를 main branch로 merge하도록 요청합니다.
5. 리뷰어(현재는 제가 맡습니다)가 승인하면 자동으로 main branch가 합쳐지고 업데이트 됩니다.
6. 완료 후 개인의 local vscode에서 git pull 명령어를 통해 가장 최근까지의 변경사항들을 업데이트합니다. (해당작업 하지않으면 conflict가 매우 빈번하게 발생할수있으니 꼭 해주셔야해요!)
