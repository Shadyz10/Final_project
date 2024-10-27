# Фронтенд-разработка проекта компании СКАН
### Описание

> Компания СКАН разработала новый API для поиска публикаций о компаниях (юридических лицах) в средствах массовой информации по их ИНН. Целевая аудитория — бизнес и ИП, которым нужно проверить добросовестность подрядчиков на основе публичных данных.
В данном проекте реализована клиентская часть сайта и взаимодействие с API.
## Клиентская часть сервиса состоит из:

* главной страницы,
* формы авторизации,
* формы для ввода параметров запроса,
* страницы с выводом результатов запроса.

### Макет проекта

Доступен по [ссылке](https://www.figma.com/file/u3MOjzYnTnirz712GrLbFv/Макет-СКАН).
**Для запуска проекта (на своем устройстве) выполнить действия в терминале:**
```
1. Поставить пакеты в корне проекта:
```bash
npm install 
```
or
```
npm i
```
2. Для запуска приложения в режиме development выполнить:
```bash
npm run dev
```
3. Для запуска приложения в режиме production необходимо собрать проект:
```bash
npm run build
```
4. После сборки выполнить:
```bash
npm run preview

#### Данные для входа

- **Логин:** `sf_student1`
- **Пароль:** `4i2385j`
- **Пример ИНН:** `7710137066`