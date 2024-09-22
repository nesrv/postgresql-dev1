# Разработка серверной части приложений PostgreSQL. Базовый курс

## Стенды


| ФИО	 | Ссылка |	Логин |	Пароль|
| -------|--------|-------|-------| 
| Потемкин Дмитрий Юрьевич |rdp.eshift.ru:12245 |	administrator |	MLRNPa$$w0rd|
| Поплаухин Иван Дмитриевич |rdp.eshift.ru:12246 |	administrator |	MLRNPa$$w0rd|
| Кетов Алексей Алексеевич |rdp.eshift.ru:12247 |	administrator |	MLRNPa$$w0rd|
| Бегенеев Владислав Юрьевич |rdp.eshift.ru:12248 |	administrator |	MLRNPa$$w0rd|
| Савранский Дмитрий Львович |rdp.eshift.ru:12249 |	administrator |	MLRNPa$$w0rd|
| Шатунова Мария Сергеевна |rdp.eshift.ru:12250 |	administrator |	MLRNPa$$w0rd|
| Серов Николай Евгеньевич |rdp.eshift.ru:13101 |	administrator |	MLRNPa$$w0rd|


В системе `Windows` для подключения к стендам следует использовать встроенную утилиту `«Подключение к удалённому рабочему столу»`. 

В `Linux` рекомендуется использовать `FreeRDP` или аналогичный клиент. 

Если в вашей организации действует ограничение на использование протокола `RDP`, обратитесь к специалистам Учебного центра для предоставления доступа на веб-шлюз.

 

## Внутри стенда:

### Виртуальные машины:

> DEV1-student-12

> Учётные данные для доступа к виртуальным машинам:

`student` - `student`

### Установка PostgreSQL в Ubuntu

> Сначала обновите списки пакетов:

```sh
sudo apt update
```


> Установите СУБД PostgreSQL

```sh
sudo apt -y install postgresql
```


> После установки СУБД откройте терминал и переключитесь на пользователя postgres с помощью команды:

```sh
sudo -i -u postgres
```


```sh
psql
```

```
\conninfo
```


```sql
sudo apt install curl
```


```sh
sudo apt install pgadmin4-desktop
```