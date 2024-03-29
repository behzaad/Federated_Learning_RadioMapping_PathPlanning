# Federated_Learning_for_RadioMapping_PathPlanning

This repository contains the Pytorch implementation of the radio mapping and path planning algorithm proposed in [1]. 




In the first step of the algorithm. the UAVs collaborate to build a model of the outage probability in the sky. For instance, in what follows, I presented the true location of the Base Stations and the outage model learned by the UAV agents. For this purpose, we use Federated Learning.


<img width="756" alt="1" src="https://user-images.githubusercontent.com/37718565/84344993-32829580-ab7a-11ea-91d4-87b0642243d2.png">



Structure of Federated Learning to estimate the outage probability: 

<img width="659" alt="2" src="https://user-images.githubusercontent.com/37718565/84345429-5692a680-ab7b-11ea-88f9-34fb2cf29b6c.png">


A sample trajectory of the UAV based on RRT-star path planning algorithm:

<img width="658" alt="Screen Shot 2020-06-15 at 16 13 46" src="https://user-images.githubusercontent.com/37718565/84701589-4421bf80-af23-11ea-807c-c4be649c1f75.png">


## Reference

If using this code for research purposes, please cite:

[1] B. Khamidehi and E. S. Sousa. "[Federated learning for cellular-connected UAVs: Radio mapping and path planning](https://arxiv.org/abs/2008.10054)." GLOBECOM 2020-2020 IEEE Global Communications Conference. IEEE, 2020.

```
@inproceedings{khamidehi2020federated,
  title={Federated learning for cellular-connected UAVs: Radio mapping and path planning},
  author={Khamidehi, Behzad and Sousa, Elvino S},
  booktitle={GLOBECOM 2020-2020 IEEE Global Communications Conference},
  pages={1--6},
  year={2020},
  organization={IEEE}
}
```
