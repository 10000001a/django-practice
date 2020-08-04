# django-practice
&lt;파이썬 웹 프로그래밍> 예제를 DRF 사용 유무의 차이에 유의하여 구현해본다.       
   
  
## .idea 관련 change가 계속 잡히는 문제
git bash를 켠 후 master branch에서 다음과 같이 입력한다.
```
mv .idea ../.idea_backup       # 부모 디렉토리에 백업해놓는다.
rm .idea                       # IDE를 닫아놓지 않았을 경우에 입력
git rm -r .idea
git commit -m "Remove .idea from repo"
mv ../.idea_backup .idea
```
