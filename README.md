# Build-pack.io

The original idea is from  
https://medium.com/@ShantKhayalian/zero-downtime-deployments-in-kubernetes-with-spring-boot-and-kubernetes-probes-73de44086298
Run

```
mvn spring-boot:build-image
```

Run

```
kubectl apply -f project.yaml
```

Go to
http://localhost:8080/api/greeting/greet

