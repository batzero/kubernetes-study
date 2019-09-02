#### Minikube 

1. 설치

설치 전 

```
grep -E --color 'vmx|svm' /proc/cpuinfo
```



Minikube 설치 

```shell
curl -Lo minikube https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64 \
  && chmod +x minikube
```



```shell
sudo mkdir -p /usr/local/bin/
sudo install minikube /usr/local/bin/
```



2. 실행

minikube 실행 

```shell
minikube start
```



Minikube clear

```shell
minikube delete
```



- 참고 사이트

 https://kubernetes.io/docs/tasks/tools/install-minikube/ 

 https://minikube.sigs.k8s.io/docs/start/linux/ 