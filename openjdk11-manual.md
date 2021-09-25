# Инструкция по установке OpenJDK11

## Windows

Шаг 1. Перейдите на сайт [adoptopenjdk.net](https://adoptopenjdk.net). 

Шаг 2. Выберите опции как на скриншоте ниже и нажмите на кнопку скачивания:

![win-adoptopenjdk](https://user-images.githubusercontent.com/72652840/134768134-4d39e53f-cf37-4609-a6e4-76707f69a4cc.png)

Шаг 3. Запустите на установку скачанный MSI-файл и нажмите кнопку "Next":

![win-step1](https://user-images.githubusercontent.com/72652840/134768145-b5f6dd05-f248-4c4f-933d-e081892d1b64.png)

Шаг 4. Прочитайте и согласитесь с условиями лицензии:

![win-step2](https://user-images.githubusercontent.com/72652840/134768150-4f17d4f2-b40a-472b-bfc3-d3cdd732f4b4.png)

Шаг 5. Выберите опции как на экране (удостоверьтесь, что установка происходит в `Program Files` и опция `Add to PATH` выбрана):

![win-step3](https://user-images.githubusercontent.com/72652840/134768156-0ed19316-5af5-483d-b846-239e411897c5.png)

Шаг 6. Нажмите на кнопку "Install":

![win-step4](https://user-images.githubusercontent.com/72652840/134768168-ae8e73f5-d324-4eca-8f6a-1ea3c6e8db11.png)

Шаг 7. Дождитесь окончания установки и нажмите на кнопку "Finish":

![win-step5](https://user-images.githubusercontent.com/72652840/134768179-63c69578-38ba-4692-be47-939875f2746b.png)


Откройте терминал и выполните команду:
```shell script
java -version
```

```
openjdk version "11.0.5" 2019-10-15
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.5+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.5+10, mixed mode)
```

**Важно**: вы должны открывать терминал уже после того, как произвели установку.
