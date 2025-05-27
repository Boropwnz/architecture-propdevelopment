# architecture-propdevelopment

## Задание 1. Разработка проверочного листа по безопасности данных

[mindmap.drawio](https://github.com/Boropwnz/architecture-propdevelopment/blob/sprint_7/Task1/mindmap.drawio)

![Картинка](https://github.com/Boropwnz/architecture-propdevelopment/blob/sprint_7/Task1/mindmap.jpg)


## Задание 2. Разработка и заполнение проверочного листа для бизнес-систем

[IB.md](https://github.com/Boropwnz/architecture-propdevelopment/blob/sprint_7/Task2/IB.md)


## Задание 3. Внешние интеграции

[Требования](https://github.com/Boropwnz/architecture-propdevelopment/blob/sprint_7/Task3/Requirements.md)

[ContextDiagram.drawio](https://github.com/Boropwnz/architecture-propdevelopment/blob/sprint_7/Task3/ContextDiagram.drawio)

![ContextDiagram.svg](https://github.com/Boropwnz/architecture-propdevelopment/blob/sprint_7/Task3/ContextDiagram.svg)

[PropDevelopment_С4_model.drawio](https://github.com/Boropwnz/architecture-propdevelopment/blob/sprint_7/Task3/PropDevelopment_С4_model.drawio)

![PropDevelopment_С4_model.svg](https://github.com/Boropwnz/architecture-propdevelopment/blob/sprint_7/Task3/PropDevelopment_С4_model.svg)


## Задание 4. Защита доступа к кластеру Kubernetes

[Таблица ролей](https://github.com/Boropwnz/architecture-propdevelopment/blob/sprint_7/Task4/roles_table.md)

[users.yaml](https://github.com/Boropwnz/architecture-propdevelopment/blob/sprint_7/Task4/users.yaml)

[roles.yaml](https://github.com/Boropwnz/architecture-propdevelopment/blob/sprint_7/Task4/roles.yaml)

[bindings.yaml](https://github.com/Boropwnz/architecture-propdevelopment/blob/sprint_7/Task4/bindings.yaml)

![Screen-shot](https://github.com/Boropwnz/architecture-propdevelopment/blob/sprint_7/Task4/ps.jpg)


## Задание 5. Управление трафиком внутри кластера Kubertnetes

[non-admin-api-allow.yaml](https://github.com/Boropwnz/architecture-propdevelopment/blob/sprint_7/Task5/non-admin-api-allow.yaml)

```
PS S:\Software Architecture\Yandex Practice\architecture-propdevelopment\Task4> cd ..\Task5\
PS S:\Software Architecture\Yandex Practice\architecture-propdevelopment\Task5> kubectl apply -f non-admin-api-allow.yaml
networkpolicy.networking.k8s.io/allow-frontend-to-backend created
networkpolicy.networking.k8s.io/admin-allow-frontend-to-backend created
```
