# Мобильное приложение "НДФЛ"

## Описание проекта

Данное приложение является простым **калькулятором НДФЛ**. Оно позволяет рассчитывать общую сумму, сумму к выплате и сумму налога к уплате.

**Налог на доходы физических лиц (НДФЛ)** — основной вид прямых налогов. Исчисляется в процентах от совокупного дохода физических лиц за вычетом документально подтверждённых расходов, в соответствии с действующим законодательством.

## Инструкция

**Для расчета выполните следующие действия:**

1. Выберите нужную ставку налога
2. Введите любое из значений: общая сумма, сумма без НДФЛ или НДФЛ
3. Значения двух остальных показателей будут рассчитаны автоматически

## Технологии

- **Язык программирования:** Kotlin
- **Рекламные технологии:** Yandex Mobile Ads SDK
- **Дизайн:** Material You
- **Динамический цвет:** Поддержка динамического изменения цветовой схемы в зависимости от обоев и темы устройства
- **Система навигации:** Predictive Back Gesture — поддержка жестов для предсказуемой навигации назад
- **Настройки:** Реализованы через файл PreferenceScreen, включающий кастомный выбор темы и опцию сохранения данных
- **Кастомные вью:** Использование собственных элементов интерфейса, таких как CustomListPreference

## Ссылки на Google Play и RuStore

Вы можете скачать и установить приложение "НДФЛ" через **Google Play** или **RuStore** по ссылкам ниже:

<table>
  <tr>
    <td><a href="https://play.google.com/store/apps/details?hl=ru&gl=ru&id=com.den.shak.ndfl">
      <img src="https://play.google.com/intl/en_us/badges/static/images/badges/ru_badge_web_generic.png" alt="Google Play" height="120">
    </a></td>
    <td><a href="https://www.rustore.ru/catalog/app/com.den.shak.ndfl">
      <img src="https://www.rustore.ru/help/icons/logo-color-dark.svg" alt="RuStore" height="120">
    </a></td>
  </tr>
</table>

## Скриншоты

Ниже представлены скриншоты приложения "НДФЛ":

<table>
  <tr>
    <td><img src="images/1.png" alt="Скриншот 1" style="width: 100%;" /></td>
    <td><img src="images/2.png" alt="Скриншот 2" style="width: 100%;" /></td>
    <td><img src="images/3.png" alt="Скриншот 3" style="width: 100%;" /></td>
  </tr>
  <tr>
    <td><img src="images/4.png" alt="Скриншот 4" style="width: 100%;" /></td>
    <td><img src="images/5.png" alt="Скриншот 5" style="width: 100%;" /></td>
    <td><img src="images/6.png" alt="Скриншот 6" style="width: 100%;" /></td>
  </tr>
</table>

## Инструкция по сборке проекта

1. **Клонируйте репозиторий:**
   ```
   git clone https://github.com/Den-88/ndfl
2. **Откройте проект в Android Studio:**
   - В главном меню выберите **"Open an existing project"** и укажите путь к проекту.

3. **Синхронизируйте Gradle:**
   - Когда появится уведомление, нажмите **"Sync Now"** для загрузки всех зависимостей.

4. **Соберите и запустите проект:**
   - Выберите режим сборки (`Debug` или `Release`).
   - Нажмите **"Run"**, чтобы начать выполнение на устройстве или эмуляторе.

## Разработчик
- **Шакуров Денис Дамирович**
