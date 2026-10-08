# SkillSwap — платформа обмена навыками

Командный учебный проект Яндекс Практикума на React и TypeScript. Пользователи могут находить людей для обмена навыками, просматривать предложения и взаимодействовать с интерфейсом платформы.

Этот репозиторий — мой fork командного проекта. **Автор портфолио: Максим Кондратьев**; приложение создано командой, ниже описан мой вклад.

[Командный репозиторий](https://github.com/Groulbands/SkillSwap_50_3/tree/develop) · [Мои коммиты](https://github.com/Groulbands/SkillSwap_50_3/commits/develop/?author=Kondrati3vMaksim)

## Мой вклад

- Разрабатывал UI-компоненты `Button`, `CheckboxCircle`, `CheckboxSquare`, `Logo` и их стили.
- Работал над `UserAvatar` и `UserCard`: отображение данных пользователя, навыков и элементов взаимодействия.
- Участвовал в разработке компонентов шапки приложения и уведомлений `Notification` / `NotificationButton`.
- Описывал параметры компонентов через TypeScript, работал с props, обработчиками событий и локальным состоянием.
- Добавлял Storybook stories для демонстрации вариантов компонентов; исправлял замечания по своим изменениям в командной разработке.

Мой вклад подтверждается историей коммитов. Разработка всего приложения, общая архитектура и вся работа с Redux не являются моей единоличной реализацией.

## Примеры кода

| Компонент | Что можно посмотреть |
| --- | --- |
| [Button](https://github.com/Kondrati3vMaksim/SkillSwap_50_3/blob/develop/src/shared/ui/Button/Button.tsx) | Типизированные параметры, варианты оформления, передача нативных атрибутов кнопки |
| [CheckboxSquare](https://github.com/Kondrati3vMaksim/SkillSwap_50_3/blob/develop/src/shared/ui/Checkbox/CheckboxSquare/CheckboxSquare.tsx) | Checkbox, состояние через props, варианты значка |
| [UserCard](https://github.com/Kondrati3vMaksim/SkillSwap_50_3/blob/develop/src/entities/user/ui/UserCard/UserCard.tsx) | Композиция компонентов, вывод навыков, действия карточки |
| [Notification](https://github.com/Kondrati3vMaksim/SkillSwap_50_3/blob/develop/src/features/notification/ui/Notification/Notification.tsx) | Отображение нового/просмотренного уведомления и обработчик действия |

## Технологии

**В моей работе:** React, TypeScript, SCSS / CSS Modules, Storybook, Git, GitHub, Figma.

**В приложении:** также Redux Toolkit, React Router, Vite, Vitest, React Hook Form и другие зависимости из [package.json](https://github.com/Kondrati3vMaksim/SkillSwap_50_3/blob/develop/package.json). Перечень стека приложения не означает, что все его части разработаны мной.

## Данные и ограничения

Учебная версия работает с JSON-моками в `public/db/` и локальными данными браузера. Это не интеграция с production backend. Сервер и секретные ключи для локального запуска не требуются.

## Результат и выводы

Мои компоненты включены в командный интерфейс платформы. Получил практику переиспользования компонентов, типизации props, согласования интерфейсов между участниками и работы с обратной связью по коду. Storybook позволяет отдельно просматривать варианты UI.

## Локальный запуск

Требования: Git, Node.js 22.12+ и npm, современный браузер. Устанавливайте зависимости из зафиксированного `package-lock.json`.

```bash
git clone --branch develop --single-branch https://github.com/Kondrati3vMaksim/SkillSwap_50_3.git
cd SkillSwap_50_3
npm ci
npm run dev
```

Откройте адрес, показанный Vite в терминале; по умолчанию [http://localhost:5173](http://localhost:5173).

### Storybook

```bash
npm run storybook
```

По умолчанию: [http://localhost:6006](http://localhost:6006).

### Сборка и проверки

| Команда | Назначение |
| --- | --- |
| `npm run build` | Проверка TypeScript и сборка Vite |
| `npm run preview` | Просмотр собранного приложения |
| `npm run test` | Запуск Vitest |
| `npm run test:coverage` | Отчёт о покрытии |
| `npm run lint` | ESLint с автоматическим исправлением файлов |
| `npm run stylelint` | Проверка SCSS |
| `npm run format` | Форматирование файлов через Prettier |

## Структура

| Каталог | Назначение |
| --- | --- |
| `src/app/` | Провайдеры и глобальные стили |
| `src/entities/` | Модели и UI сущностей |
| `src/features/` | Пользовательские функции |
| `src/pages/` | Страницы |
| `src/shared/` | Общие типы, утилиты, UI |
| `src/store/` | Redux store и типизированные хуки |
| `src/widgets/` | Составные блоки интерфейса |
| `public/db/` | JSON-моки |

## Дальнейшее развитие

Углубить понимание управляемых компонентов и потока данных React, проверить пограничные состояния карточки пользователя и расширить проверки UI. Эти пункты — планы, а не уже выполненные задачи.

Исходная командная история Git сохранена. Документация портфолио обновляется в личном fork.

[Telegram](https://t.me/Phoenixbelike)
