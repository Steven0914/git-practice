# git-practice


```c
#include<stdio.h>

int main(){
printf("2025001001 김소웨");
// 본인의 학번과 이름을 수정해주세요.

}

```


### 프로젝트를 위한 최소한의 깃 명령어

```bash
git clone
git status
git add 파일 이름
git commit -m “커밋 내용”
git switch -c  브랜치 이름
git merge 합칠 브랜치
git pull
git push 
```

위 8개의 명령어만 알면 협업하는데 문제 지장 X

### 프로젝트 진행 순서

1. 처음에 git clone으로 프로젝트 복제
2. 이슈에 본인이 수행할 작업을 달기
3. 작업할 브랜치 파기 (git switch -c  브랜치 이름)
4. 본인이 만들기능 구현
5. 본인이 추가(수정)한 파일 추가 (git status, git add 파일 이름)
6. 커밋(저장) (git commit -m “커밋 내용 (#이슈번호)”)
7. 현재 최신본 업데이트 (git switch main, git pull)
8. 구현한 것과 최신본 합치기(git switch 작업브랜치, git merge main)
9. 파일 업로드 (git push)
10. 풀리퀘스트로 레포지토리 업데이트
