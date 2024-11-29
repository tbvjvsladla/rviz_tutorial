WSL CUDA 가속기 설정 후</br>
Rviz visuial기능이 잘 동작하는지</br>
확인하는 패키지입니다.</br>
위 패키지를 작업공간(catkin_ws/src)에서 </br>
```git
git clone https://github.com/tbvjvsladla/rviz_tutorial.git
```
위 명령으로 패키지를 다운로드 받고 작업공간 이동 -> `catkin_make`를 수행한 뒤<br>
(아래 명령은 예시입니다)
```bash
cd ~/catkin_ws
catkin_make
```
패키지 빌드를 완료한 후에는 아래 명령을 실행하기 바랍니다.
```bash
roslaunch rviz_tutorial demo_car.launch
```
명령어를 입력하면 아래의 gif 실행결과가 출력됩니다.
![Demo GIF](demo.gif)</br>
