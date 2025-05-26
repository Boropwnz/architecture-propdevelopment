| Роль  | Права роли | Группы пользователей |
| --- | --- | --- |
| Название роли, которое отвечает требованиям RBAC в Kubernets. | Укажите права, которые необходимо выдать этой роли. | Выделите группы пользователей в организации, которые нужно связать с этой ролью. |
| dev-reader | get, list, watch в пространстве имен dev | Разработчики |
| dev-writer | create, update, delete, get, list, watch в пространстве имен dev | DevOps |
| prod-writer | create, update, delete, get, list, watch в пространстве имен prod | DevOps |
| prod-reader | get, list, watch в пространстве имен prod | Поддержка |
| secrets-reader | get, list в пространстве имен secure | Специалист по информационной безопасности |
