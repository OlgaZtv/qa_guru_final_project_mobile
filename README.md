# Автоматизированные тесты на мобильное приложение Wikipedia 

## Покрыт следующий функционал

- Поиск в приложении
- Прохождение начального экрана
- Проверка настроек приложения

## Технологический стек
Java, Gradle, JUnit5, IntelliJ IDEA, Appium, Selenide, Browserstack, Jenkins, Allure TestOps, Jira, Github
<br/>
<p  align="left">
<code>
<img src="https://i.ibb.co/gtnxLqH/java.png" width="40" height="40"  alt="Java"/>
<img src="https://i.ibb.co/0jBcyBY/gradle-icon.png" width="40" height="40"  alt="Gradle"/>
<img src="https://i.ibb.co/PgvTPCh/Junit5.jpg" width="50" height="40"  alt="JUnit 5"/>
<img src="https://i.ibb.co/8YWqxkP/Intelleji.png" width="40" height="40"  alt="IDEA"/>
<img src="https://cdn.coursehunter.net/category/appium.png" width="45" height="40"  alt="Appium"/>
<img src="https://i.ibb.co/SmBNT3B/Selenide.jpg" width="50" height="40"  alt="Seleide"/>
<img src="https://cdn.freebiesupply.com/logos/thumbs/2x/browserstack-logo.png" width="45" height="40"  alt="Browserstack"/>
<img src="https://i.ibb.co/4p3B78k/Jenkins.jpg" width="40" height="40"  alt="Jenkins"/>
<img src="https://i.ibb.co/37MYfX4/allure.jpg" width="40" height="40"  alt="Allure TestOps"/>
<img src="https://i.ibb.co/RSv0PZv/Jira.png" width="40" height="40"  alt="Jira"/>
<img src="https://i.ibb.co/mCQd2Cx/Github.png" width="40" height="40"  alt="Github"/>
</code>
</p>

## Как запустить

### Перед выполением необходимо:

* запустить сервер (browserstack or selenoid)

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
<a href="https://ibb.co/n7h7PmB"><img src="https://i.ibb.co/D939rWY/Olga-Ztv-final-mobile-project-Jenkins.png" alt="Olga-Ztv-final-mobile-project-Jenkins" border="0"></a>

Параметры запуска <br >
<a href="https://ibb.co/X7JDfrY"><img src="https://i.ibb.co/x15YKtF/Jenkins.png" alt="Jenkins" border="0">

### Отчёт о прохождении автотестов в Allure Report
<a href="https://ibb.co/M1XY2Cm"><img src="https://i.ibb.co/kDdRHSt/Allure-Report.png" alt="Allure-Report" border="0"></a>

### Хранение тестовой документации в Allure TestOps
<a href="https://ibb.co/gDqH4Xc"><img src="https://i.ibb.co/vJygXrM/Allure-Test-Ops.png" alt="Allure-Test-Ops" border="0"></a>

### Dashboard
<a href="https://ibb.co/XJmzBpm"><img src="https://i.ibb.co/JkXzL2X/Allure-Test-Ops-dash.png" alt="Allure-Test-Ops-dash" border="0"></a>

### Интерграция с Jira
<a href="https://ibb.co/3dBz4mJ"><img src="https://i.ibb.co/B3qNc21/Jira.png" alt="Jira" border="0"></a>


