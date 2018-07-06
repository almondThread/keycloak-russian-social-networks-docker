# Пример сборки docker-образа с поддержкой VK логина

Сборка основана на официальном репозитории [Docker image for Keycloak project](https://github.com/jboss-dockerfiles/keycloak)

В папке *target* находятся необходимые для поддержки VK файлы собранные в [этом](https://github.com/almondThread/keycloak-russian-social-networks/tree/vk-social-provider) форке keycloak.

Сборка выполняется стандартной командой:

```
docker build .
```
