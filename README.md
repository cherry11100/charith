apiVersion:
v1
kind: Pod
metadata:
name: 2048-pod
labels:
app: 2048-ws
spec:
containers:
name:
2048-container
image:
blackicebird/2048
ports:
- containerPort:
80
