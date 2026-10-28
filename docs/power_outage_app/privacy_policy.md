# Політика конфіденційності

Застосунок «Графік відключень Волинь» (Android, ua.volyn.poweroutage). Діє з 28 жовтня 2026 року.

Ця ж політика з оформленням: [privacy-policy.html](privacy-policy.html). [English version below](#privacy-policy).

Застосунок безкоштовний і неофіційний: його створив Mykyta Synieok (далі - розробник), він не пов'язаний з ПрАТ «Волиньобленерго». Реєстрація не потрібна, імені, телефону чи email застосунок не просить.

## Що зберігається лише на вашому телефоні

Адреси, які ви додали, графіки відключень, аварійні та планові відключення, історія змін і налаштування зберігаються лише на пристрої. Розробнику вони не надсилаються.

## Що надсилається стороннім сервісам, щоб застосунок працював

- **Сайт ПрАТ «Волиньобленерго» (energy.volyn.ua)** - назва населеного пункту й вулиці, щоб отримати графік відключень, аварійні та планові відключення. Номер будинку не надсилається: застосунок порівнює його на телефоні. Запити йдуть і у фоні, під час автоматичних перевірок.
- **Підказки під час додавання адреси** - текст, який ви вводите, надсилається до сервісу Photon (komoot, на основі OpenStreetMap) для підказок населених пунктів і до API «Нової пошти» для підказок вулиць.

Як і будь-який сайт, ці сервіси отримують IP-адресу вашого пристрою і обробляють запити за власними правилами.

## Аналітика й звіти про збої (Google Firebase)

- **Firebase Analytics** збирає знеособлену статистику використання: запуски й сеанси, оновлення застосунку, модель пристрою, версії Android і застосунку, приблизну країну чи регіон (за IP-адресою), ідентифікатор встановлення застосунку, а також технічну подію про запізнення фонових перевірок (лише числа). Адреси й графіки до аналітики не потрапляють.
- **Firebase Crashlytics** надсилає звіти про збої: технічний опис помилки, модель пристрою, версії Android і застосунку, ідентифікатор встановлення.

Ці дані допомагають знаходити помилки й робити фонові перевірки надійнішими. Їх обробляє Google: [конфіденційність у Firebase](https://firebase.google.com/support/privacy).

## Реклама (Google AdMob)

Унизу головного екрана показується рекламний банер Google AdMob. Щоб показувати й вимірювати рекламу, AdMob може збирати рекламний ідентифікатор пристрою, IP-адресу, відомості про пристрій і взаємодію з рекламою, а також показувати персоналізовану рекламу. Докладніше: [як Google використовує дані з застосунків партнерів](https://policies.google.com/technologies/partner-sites). Рекламний ідентифікатор можна скинути або видалити в налаштуваннях Android (Google - Реклама, або Конфіденційність - Реклама).

## Сповіщення й фонова робота

Сповіщення формуються на телефоні. Фонові перевірки лише звертаються до сайту energy.volyn.ua, як описано вище.

## Безпека

Застосунок звертається до всіх сервісів через захищене з'єднання (HTTPS).

## Зберігання й видалення даних

Дані на телефоні видаляються, коли ви видаляєте адресу, очищуєте історію або видаляєте застосунок. Дані аналітики, звітів про збої й реклами зберігаються в Google відповідно до [Політики конфіденційності Google](https://policies.google.com/privacy). Розробник не може пов'язати їх з конкретною людиною, але з питаннями можна звертатися на email нижче.

## Діти

Застосунок не призначений для дітей до 13 років і свідомо не збирає їхніх даних.

## Зміни політики

Оновлена політика публікується на цій сторінці зі зміненою датою.

## Контакт

[n.sineok@gmail.com](mailto:n.sineok@gmail.com)

---

# Privacy Policy

"Графік відключень Волинь" (Volyn Power Outage Schedule) app for Android, ua.volyn.poweroutage. Effective October 28, 2026.

The app is free and unofficial. It was created by Mykyta Synieok ("the developer") and is not affiliated with PrJSC "Volynoblenergo". No registration is required; the app does not ask for your name, phone number or email.

## Data stored only on your device

The addresses you add, outage schedules, emergency and planned outages, change history and settings are stored only on your device. They are not sent to the developer.

## Data sent to third-party services for the app to work

- **The website of PrJSC "Volynoblenergo" (energy.volyn.ua)**: the settlement and street name, to get the outage schedule and emergency and planned outages. The house number is not sent; it is matched on the device. Requests are also made in the background during automatic checks.
- **Suggestions while adding an address**: the text you type is sent to Photon (komoot, based on OpenStreetMap) for settlement suggestions and to the Nova Poshta API for street suggestions.

Like any website, these services receive your device's IP address and process requests under their own policies.

## Analytics and crash reports (Google Firebase)

- **Firebase Analytics** collects pseudonymous usage statistics: app opens and sessions, app updates, device model, Android and app versions, approximate country or region (from the IP address), an app instance identifier, and a technical event about delayed background checks (numbers only). Addresses and schedules are not sent to analytics.
- **Firebase Crashlytics** sends crash reports: a technical description of the error, device model, Android and app versions, and an installation identifier.

This data helps find bugs and make background checks more reliable. It is processed by Google: [Privacy and Security in Firebase](https://firebase.google.com/support/privacy).

## Advertising (Google AdMob)

A Google AdMob banner is shown at the bottom of the main screen. To serve and measure ads, AdMob may collect the device advertising ID, IP address, device information and ad interactions, and may show personalized ads. More: [How Google uses information from sites or apps that use its services](https://policies.google.com/technologies/partner-sites). You can reset or delete the advertising ID in Android settings (Google - Ads, or Privacy - Ads).

## Notifications and background work

Notifications are created on the device. Background checks only contact energy.volyn.ua as described above.

## Security

The app uses encrypted connections (HTTPS) for all services.

## Retention and deletion

Data on the device is deleted when you remove an address, clear the history or uninstall the app. Analytics, crash and advertising data is retained by Google under the [Google Privacy Policy](https://policies.google.com/privacy). The developer cannot link it to a specific person, but you can contact the developer with any questions at the email below.

## Children

The app is not directed to children under 13 and does not knowingly collect their data.

## Changes

Updated versions of this policy are published on this page with a new effective date.

## Contact

[n.sineok@gmail.com](mailto:n.sineok@gmail.com)
