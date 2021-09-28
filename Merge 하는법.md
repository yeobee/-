## Merge 하는법

------

- 작업 중인 브랜치
- git add .
- git commit -m "커밋 메시지"
- git push
  - git push --set-upstream origin "브랜치명"
- git checkout develop (브랜치 이동)
- git pull
- git merge 작업한 브랜치
- 민트색으로 영어 어쩌구 나오면 :q 입력
- [conflict 안났을 경우]
  - git push
- [conflict 났을 경우]
  - vscode or eclipse 열어서 수정
  - git add .
  - git commit -m "커밋 메시지"
  - git push