> **Security Notice: Please remember to change the `admin.check.signSecret`, `admin.root.user.name` and `admin.root.user.password` value before you deploy to production environment.**

## 1. Project download to local
```
git clone https://github.com/apache/dubbo-admin.git
```

## 2. Switch project directory
```
cd dubbo-admin/deploy/charts/dubbo-admin
```

## 3. Install dubbo-admin
```
helm install dubbo-admin -f values.yaml .
```
