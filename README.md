1. Environment details

The environment involves an agent to navigate and collect yellow bananas, which will yield a positive 1 reward. However, there are also blue bananas, which gives negative 1 reward. Thus, the scope is to collect as many yellow bananas as possible and avoid the blue ones. The environment is considered solved if the mean accumulated reward is 13 over 100 consecutive episodes. The enviroment has a state dimension of 37 and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction. There are four actions that the agent can take: 0(forward), 1(backward), 2(left) and 3(right).

2. Requirements
In order to run the project, Python3 and Unity ML-Agents are needed. Moreover, the following packages with the required version are needed:
tensorflow: 1.7.1
Pillow: Greater than 4.2.1
matplotlib
numpy: Greater than 1.11.0
jupyter
pytest>=3.2.2
docopt
pyyaml
protobuf: 3.5.2
grpcio: 1.11.0
torch: 0.4.0
pandas
scipy
ipykernel

The project environment can be downloaded from the following links, depending on the OS used:
- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

3. How to run the code?
The main file is represented by the jupyter notebook. Then, two additional Python files are imported in it. The code can be run by firstly running the second cell in order to define the environment, then run the eighth cell (last one).
