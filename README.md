# Автоматизированные тесты на мобильное приложение Wikipedia 

## Покрыт следующий функционал

- Прохождение начального экрана
- Search by query
- Add new language

## Технологический стек
Java, Gradle, JUnit5, IntelliJ IDEA, Appium, Selenide, Browserstack, Jenkins, Allure TestOps, Jira, Github, Telegram
<a href="https://github.com/angry-qa/vkc-demo">
<img src="https://starchenkov.pro/qa-guru/img/skills/Java.svg" width="40" height="40"  alt="Java"/>
<img src="https://starchenkov.pro/qa-guru/img/skills/Gradle.svg" width="40" height="40"  alt="Gradle"/>
<img src="https://starchenkov.pro/qa-guru/img/skills/JUnit5.svg" width="40" height="40"  alt="JUnit 5"/>
<img src="https://starchenkov.pro/qa-guru/img/skills/Intelij_IDEA.svg" width="40" height="40"  alt="IDEA"/>
<img src="https://starchenkov.pro/qa-guru/img/skills/Selenide.svg" width="40" height="40"  alt="Seleide"/>
<img src="https://starchenkov.pro/qa-guru/img/skills/Jenkins.svg" width="40" height="40"  alt="Jenkins"/>
<img src="https://starchenkov.pro/qa-guru/img/skills/Allure_EE.svg" width="40" height="40"  alt="Allure TestOps"/>
<img src="https://starchenkov.pro/qa-guru/img/skills/Jira.svg" width="40" height="40"  alt="Jira"/>
<img src="https://starchenkov.pro/qa-guru/img/skills/Github.svg" width="40" height="40"  alt="Github"/>
<img src="https://starchenkov.pro/qa-guru/img/skills/Telegram.svg" width="40" height="40"  alt="Telegram"/>
</a>

## Как запустить

### Перед выполением необходимо:

* запустить сервер (browserstack or selenoid)
* указать окружение (for telegram notification)
* комментарий (for telegram notification)

Запуск тестов с помощью browserstack:

```bash
gradle clean test -DdeviceHost=browsertack
```

Запуск тестов с помощью selenoid:

```bash
gradle clean test -DdeviceHost=selenoid
```

Запуск тестов с незаполненными свойствами browserstack:

```bash
gradle -DdeviceHost=browserstack -Duser={put here browserstack user} -Dkey={put here browserstack access key} -Dapp={put here your browserstack app id} clean test
```
 
### Запуск в Jenkins
Статистика по запускам <br >
<a href="https://ibb.co/nnKgcv6"><img src="https://i.ibb.co/CMS17Zm/statistic-jenkins.png" alt="Статистика по запускам" border="0" /></a>

Параметры запуска <br >
<a href="https://ibb.co/zbNbgHb"><img src="https://i.ibb.co/Y8b8ST8/jenkins-parametrs.png" alt="jenkins-parametrs" border="0" /></a>

### Отчёт о прохождении автотестов в Allure Report


### Хранение тестовой документации в Allure TestOps

### Test Cases

### Dashboard


### Allure пример видео о прохождении тестов


### Интерграция с Jira


### Уведомления о прохождении автотестов в Telegram


