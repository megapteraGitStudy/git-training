### git remote 
- 현재 깃 디렉토리(로컬 리포지토리)와 연결된 원격 리포지토리 목록을 나타낸다.

### git remote add 리모트 이름 리모트url
- 깃 디렉토리에 새로운 원격 리포지토리를 연결한다.

### git remote -v
- 깃 디렉토리에 연결된 리모트의 이름과 url을 동시에 보여준다.

### git remote show 리모트 이름
해당 리모트의 다양한 정보를 보여준다.
url
- 해당 리모트의 url을 보여준다. 

HEAD branch
- 정확하게 모르겠다. 

Remote branches
- tracked : fetch가 된 리모트의 브랜치 
- new : 아직 fetch가 안된 리모트의 브랜치 


- fetch -> add만 하면 리모트에 어떤 브랜치가 있는지 정보를 모른다. 
- fetch를 해야 어떤 내용이 리모트에 존재 하는지 알 수 있다.
- merge, checkout(switch), rebase ...