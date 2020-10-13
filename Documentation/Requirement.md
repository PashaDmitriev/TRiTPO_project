# 1 Введение

<a name="appointment"/>

## 1.1 Назначение
Продукт нацелен на людей старшей возрастной группы, поскольку им не всегда удобно просматривать различные сайты в поиске необходимых им новостей

## 2.2 Интерфейс пользователя
Интерфейс должен быть максимально простым, понятным и крупным для удобства использования.
Окно входа в приложение.  
![](https://github.com/PashaDmitriev/TRiTPO_project/tree/main/Documentation/Mockups/ApplicationLoginWindow.PNG)  
Окно регистрации нового пользователя.  
![Окно регистрации нового пользователя](https://github.com/PashaDmitriev/TRiTPO_project/tree/main/Documentation/Mockups/RegistrationWindow1.PNG)  
Окно регистрации нового пользователя после ввода имени, уже зарегистрированного в приложении.  
![Окно регистрации нового пользователя после ввода имени, уже зарегистрированного в приложении](https://github.com/PashaDmitriev/TRiTPO_project/tree/main/Documentation/Mockups/RegistrationWindow2.PNG)  
Окно входа для зарегистрированного пользователя.  
![Окно входа для зарегистрированного пользователя](https://github.com/PashaDmitriev/TRiTPO_project/tree/main/Documentation/Mockups/LoginScreenForTheRegisteredUser.PNG)  
Главное окно приложения (пользователь зарегестрирован).  
![Главное окно приложения](https://github.com/PashaDmitriev/TRiTPO_project/tree/main/Documentation/Mockups/MainWindow1.PNG)  
Главное окно приложения после выбора новости в таблице (пользователь зарегестрирован).  
![Главное окно приложения после выбора новости в таблице](https://github.com/PashaDmitriev/TRiTPO_project/tree/main/Documentation/Mockups/MainWindow2.PNG)  
Главное окно приложения после выбора новости в таблице (анонимный пользователь).  
![Главное окно приложения после выбора новости в таблице](https://github.com/PashaDmitriev/TRiTPO_project/tree/main/Documentation/Mockups/MainWindowAnonymousUser.PNG)  
Окно настройки профиля пользователя.  
![Окно настройки профиля пользователя](https://github.com/PashaDmitriev/TRiTPO_project/tree/main/Documentation/Mockups/SettingUpAUserProfile.PNG)

<a name="user_specifications"/>

## 2.3 Характеристики пользователей

<a name="user_classes"/>

### 2.3.1 Классы пользователей

| Класс пользователей | Описание |
|:---|:---|
| Анонимные пользователи | Пользователи, которые не хотят регистрироваться в приложении. Имеют доступ к частичному функционалу |
| Зарегистрированные пользователи | Пользователи, которые вошли в приложение под своим именем (псевдонимом), желающие просматривать краткую информацию о новостях, отобранных согласно их предпочтениям. Имеют доступ к полному функционалу |

<a name="application_audience"/>

### 2.3.2 Аудитория приложения

<a name="target_audience"/>

#### 2.3.2.1 Целевая аудитория
Люди старшей возрастной категории со средним или выше среднего уровнем образования, обладающие минимальной технической грамотностью.

<a name="collateral_audience"/>

#### 2.3.2.2 Побочная аудитория
Люди средней возрастной категории, обладающие вышеперечисленными качествами.

<a name="assumptions_and_dependencies"/>

## 2.4 Предположения и зависимости
1. Приложение не работает при отсутствии подключения к Интернету;
2. Приложение не обрабатывает данные RSS-лент, недоступных в момент запроса.

<a name="system_requirements"/>
