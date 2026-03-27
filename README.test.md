# OS2IoT-backend – test

This branch contains <https://github.com/itk-dev/OS2iot-backend/tree/feature/docker-setup-cleanup> with

1. https://github.com/itk-dev/OS2iot-backend/tree/feature/application-metadata
2. https://github.com/itk-dev/OS2iot-backend/tree/feature/application-contact-persons

on top and in that order.

``` shell
git remote add upstream https://github.com/itk-dev/OS2iot-backend || true
git fetch upstream
git reset --hard upstream/feature/docker-setup-cleanup
git merge --no-ff upstream/feature/application-metadata
git merge --no-ff upstream/feature/application-contact-persons
```
