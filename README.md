# helm-charts init


Use this :
```helm install profile-service ./profile-service --set serviceAccount.create=false --set serviceAccount.name=ss-postgres-cloudsql-ksa```

When want to use a service account that already exists in the cluster.

Simple helm install:
```helm install profile-service ./profile-service```

To delete deployment
```helm delete profile-service```

To check if helm chart is correctly linted:
```helm lint ./profile-service```