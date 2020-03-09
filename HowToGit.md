# git 사용하는 방법

## 내컴퓨터에서 내용을 추가로 수정해보기!!

Github에서 `git pull`하지않고 작성해서 결과 비교하기!!

----

1. github.com - 회원가입 및 로그인
2. new repository(저장소를 생성)
3. 내컴퓨터에서 다운받을 위치에서

```sehll
$ git cㅣone [git주소.git]
$ cd [repository폴더]
```

4. 필요한 data를 생성, 작성....
5. data를 첨부

```shell
$ git add [폴더 및 파일명]    // 파일의 갯수가 100개이상/100mb 이상을 한꺼번에 첨부x
                            // 한달기준 1기가 제한
  
```

6. 첨부된 data내용을 작성

```shell
$ git commit -m "[첨부내용을 작성 자세하게]"
```

7. add와  commit을 취소하고 다시 작성 할수 있도록 내용 수정

```shell
$ git reset					// 추가기능에는 git reset HEAD[~순서] 가 있다.
```



1. 상태꼭 자주 확인

```shell
$ git status                // 붉은색 글씨는 첨부가 안된것
                            // 녹글씨는 첨부된것 (new, modify....)
                            // 내용이 없는 것은 전송할 자료가 없거나, commit이되어 전송전 상태
```

8. 자료를 전송

```shell
$ git push 					// 사용자 설정이 되지있지 않으며, git config를 통해서 등록!!
```

