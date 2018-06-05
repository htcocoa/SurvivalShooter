# SurvivalShooter

이 프로젝트는 유니티 교육을 위해 제작되었다.

이 프로젝트는 아이가 꿈속에서 괴물로 변한 인형들을 총으로 쏴서 없애는 게임이다.

![Survival1](http://drive.google.com/uc?export=view&id=15i2IP0r-Bbeo6Ekorm2jzd-wqisgO7vb)

이 게임을 시작하면 주인공이 방 한가운데 있으며 상단에 점수가, 왼쪽 하단에 남은 체력이 표시된다.
wasd키로 주인공을 이동시킬 수 있으며 마우스 클릭으로 총을 발사할수 있다. 주인공은 마우스 방향을 바라보며 총은 바라보고 있는 방향으로 발사 된다.
주인공과 총알은 장애물을 통과 할 수 없다.

![Survival2](http://drive.google.com/uc?export=view&id=128Ow213kVCrqW4sJXAC6aKhTTpCgn7Z9)
![Survival6](http://drive.google.com/uc?export=view&id=1WlMuZXa1aZio4HAlwhBZ5SyuIVwReoF5)

적은 Zombunny, Zombear, Helephant의 세가지가 있으며 각자 정해진 스폰장소에서 고유한 체력과 공격력을 갖고 일정한 시간마다 스폰된다. 
적들은 주인공을 향하여 자동으로 움직이고 주인공이 근처에 있으면 주인공에게 공격력만큼의 피해를 준다. 
주인공의 공격은 10만큼의 피해를 주며 주인공은 100의 체력을 가지고 있다.
적들은 체력이 모두 없어지면 죽으며 죽을때 정해진 만큼의 점수를 올려준다.

종류|체력|공격력|공격간격|점수|스폰간격
----|----|----|----|----|----
Zombunny|30|3|0.2|10|1
Zombear|70|15|0.5|30|3
Helephant|100|70|0.5|10|10

![Survival4](http://drive.google.com/uc?export=view&id=1f-vc0RajhEtI8sFeZtHfiKX2B1xStQ4e)

주인공이 공격을 받으면 위와 같이 화면이 붉은색으로 빛나고 주인공의 체력이 0이 되면 주인공이 사망한다.
주인공이 사망하면 게임오버가 된다.

![Survival5](http://drive.google.com/uc?export=view&id=1f-HZNl1vgMzPZP60sF_WkHJnnCOWibuD)
게임오버가 되면 위와 같은 화면이 뜨고 자신의 최종점수를 확인할 수 있다. 
게임오버가 된후 5초가 지나면 자동으로 게임이 재시작 된다.
