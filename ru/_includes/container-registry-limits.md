#### Квоты {#container-registry-quotas}

Вид ограничения | Значение
--- | ---
Максимальное количество [реестров](../container-registry/concepts/registry.md) в одном [облаке](../resource-manager/concepts/resources-hierarchy.md#cloud) | 10
Количество одновременных запусков [сканирования](../container-registry/concepts/vulnerability-scanner.md) [Docker-образа](../container-registry/concepts/docker-image.md) в одном облаке | 10

#### Лимиты {#container-registry-limits}

Вид ограничения | Значение
--- | ---
Максимальный размер одного слоя Docker-образа | 150 ГБ
Максимальное количество Docker-образов в одном [репозитории](../container-registry/concepts/repository.md), которое может проверить тестовый запуск [политики автоматического удаления Docker-образов](../container-registry/concepts/lifecycle-policy.md) | 50 000