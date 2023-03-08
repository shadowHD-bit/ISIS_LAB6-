# ISIS 6
Запустить приложение2 в Kubernetes, настроить readiness probe

Скопируйте репозиторий:
```
git clone https://github.com/shadowHD-bit/ISIS_LAB6.git
```


Установите все зависимости, ели требуется проверить работу приложения локально:
```
npm install
```

Выполните команду:
```
kubectl apply -f .\k8s\node-deployment.yaml
```

Провербте работу Readiness Probe