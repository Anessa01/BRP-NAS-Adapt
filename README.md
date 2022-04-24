# BRP-Nas
Note: please use Python >= 3.6.0 and Tensorflow >= 1.13.0.

To run the device_runner on Nasbench101 & Nasbench201:

`cd BRP-NAS-Adapt`

`python -m eagle.device_runner --model nasbench201 --device desktop --cfg configs/measurements/desktop_nasbench201_local.yaml`

`python -m eagle.device_runner --model nasbench101 --device desktop --cfg configs/measurements/desktop_nasbench101_local.yaml`

the results will be saved at `results/nasbench101/latency/desktop/results/results0.pickle` & `results/nasbench201/latency/desktop/results/results0.pickle`

