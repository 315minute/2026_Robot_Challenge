# 2026 AI 로봇 챌린지 11조 repo

모두 화이팅~

## Docker 사용법

`docker compose up -d --build` 
하면 뭐가 다운로드 되기 시작합니다. image를 만드는거에요.


`docker exec -it robot_container /bin/bash`
하면 container안에 들어갈 수 있게됩니다. container란 단순하게 생각하면 local환경이 아닌 우리가 세팅해놓은 환경에서 코드를 굴릴수 있다는 겁니다. 이후 ctrl + D를 이용하면 container에서 빠져나올 수 있습니다.

대회를 준비하며 더 많은 라이브러리들이 필요할텐데 이는 Dockerfile을 수정하면 됩니다. 이때 반드시 맨 마지막줄에 추가해주세요.

