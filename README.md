# codewings car game
python3, pygame 필요

* run
  
  `python3 pygame_car.py`
 
* AI 작성

  `AI.py`

```

          |       ***     | 세로 0 지점
          |       ***     |
          |       ***     |
          |       2**     |
          |               |
          |               |
          |               |
          |               | 세로길이 0 ~ 450
          |               |
          |               |
          |    @@@        |
          |    @@@        |
          |    @@@        |
          |    1@@        | 세로 450 지점
    가로 160지점        가로 660지점

    자동차 가로 크기 : 70
    자동차 세로 크기 : 140
        
my_x : 현재 내 자동차의 가로축 위치 (1번 점의 가로 위치)
my_y : 현재 내 자동차의 세로축 위치 (1번 점의 세로 위치)
my_speed : 현재 내 자동차의 가로축 속도(left는 왼쪽 right은 오른쪽)
blue_x : 파란 자동차의 가로축 위치 (2번 점의 가로 위치)
blue_y : 파란 자동차의 세로축 위치 (2번 점의 세로 위치)

```
