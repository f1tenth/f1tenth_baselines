# F1TENTH Benchmarks and Baseline Solutions
This is the repository for the baseline solutions from our paper 

*F1TENTH: An Open-source Evaluation Environment for Continuous Control and Reinforcement Learning* 

in the Post Proceedings of the NeurIPS 2019 Demonstration and Competition Track. For the Gym Environment, please see the repo [here](https://github.com/f1tenth/f1tenth_gym).

If you find our environment or the baseline solutions useful, please cite:
```
@InProceedings{okelly2020f110,
	  title={F1TENTH: An Open-source Evaluation Environment for Continuous Control and Reinforcement Learning},
	  author={O'Kelly, Matthew and Zheng, Hongrui and Karthik, Dhurv and Mangharam, Rahul},
	  booktitle={Post Proceedings of the NeurIPS 2019 Demonstration and Competition Track},
	  year={2020},
	  editor={Hugo Jair Escalante and  Raia Hadsell},
	  series={Proceedings of Machine Learning Research},
	  publisher={PMLR}
	  }
```

## Benchmark I: Static Kinodynamic Planning
The first benchmark involves a known track and a single vehicle. The objective is to navigate the track in a minimal amount of time. The task is considered successful only if the trajectory is collision-free.

## Benchmark II: Online Kinodynamic Planning
The second benchmark involves a known map with obstacles. The location of obstacles in the map is not known prior to runtime. The agent must detect and avoid static obstacles in real time.

## Benchmark III: Multi-agent Dynamic Games
The third benchmark involves a known map with two or more agents simultaneously driving on the map. The objective of each agent is to finish a number of laps faster than all other agents without collision.
