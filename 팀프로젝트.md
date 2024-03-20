## conflict 충돌 해결 방법

모두가 최신 커밋 내용을 가지고 있다고 가정하자.

```text
Hello!
```

위의 글은 Conflict.txt 파일에 기록되어 있다.

모두가 기존 Conflict.txt 파일을 다르게 수정하고 Commit 한 후 push 하려고 하면 아래와 같이 Git Error가 발생한다.

![[Pasted image 20240320100630.png]]

해결 방법은 이슈 #3 에 올라온 답변에 있다.

만약 `git reset` 명령어를 사용하지 않고 `git pull` 사용하면 아래와 같이 내용이 추가된다.
```text
>>>>>>> 1234567
Hello!
=======
Hello!
I am ground
>>>>>>> HEAD
```

이 때 아래와 같이 수정하면 충돌 사항을 해결할 수 있다.
```text
I am ground
```