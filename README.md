# carla-leaderboard2022
6/6/2023 8:22:02 PM: system setup complete https://leaderboard.carla.org/get_started/  
6/6/2023 8:22:21 PM: for the autonomous agent, npc_agent.py. This script works to drive the agent. TODO: submit agent for leaderboard results https://leaderboard.carla.org/submit/  
```
(py37) nsambhu@SAMBHU19:~/github$ ${LEADERBOARD_ROOT}/scripts/make_docker.sh 
Copying CARLA Python API
Copying Scenario Runner
Copying Leaderboard
Copying team code folder
Building docker
/home/nsambhu/github/leaderboard/scripts/make_docker.sh: line 89: docker: command not found
```
6/6/2023 8:28:13 PM: TODO: install docker https://docs.docker.com/desktop/install/linux-install/  
6/6/2023 8:38:42 PM: failure at kvm step. Try alternate install https://docs.docker.com/engine/install/ubuntu/#install-using-the-repository  
6/6/2023 8:47:52 PM: docker installed. Retry submission: 
```
(py37) nsambhu@SAMBHU19:~/github$ ${LEADERBOARD_ROOT}/scripts/make_docker.sh
Copying CARLA Python API
Copying Scenario Runner
Copying Leaderboard
Copying team code folder
Building docker
ERROR: permission denied while trying to connect to the Docker daemon socket at unix:///var/run/docker.sock: Get "http://%2Fvar%2Frun%2Fdocker.sock/_ping": dial unix /var/run/docker.sock: connect: permission denied
```
6/6/2023 8:50:04 PM: solution attempt: https://stackoverflow.com/a/48450294  
6/6/2023 8:50:59 PM: error persists. Reboot machine.  
6/6/2023 8:53:53 PM: error gone. Build in progress.  
