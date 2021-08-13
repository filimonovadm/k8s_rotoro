версия nginx определяется в Deployment.yaml

для удаления созданных сущностей
kubectl -n myapp-deployment delete pod,svc --all

изменение количества создаваемых реплик определяется в манифесте yaml файла replicas:

