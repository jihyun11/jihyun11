```console
jihyun11@aws:~$ kubectl get engineer jihyun11 -o yaml
```

```yaml
apiVersion: jihyun.dev/v1
kind: Engineer
metadata:
  name: jihyun11
  labels:
    role: backend/infra
spec:
  languages: [kotlin]
  platform: [aws, eks, docker]
  interests:
    - kubernetes
    - database
status:
  phase: Running
  message: "커 피 좋 아 인간입니다"
```

```console
jihyun11@aws:~$ █
```
