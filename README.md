# 🎮 P2P Tic-Tac-Toe | P2P Хрестики-Нолики

[English](#english) | [Українська](#українська)

---

## English

### 🌟 Live Demo
**Play now:** [https://dneese.github.io/P2P-tic-tac-toe/](https://dneese.github.io/P2P-tic-tac-toe/)

![Game Screenshot](screenshot.png)

### 📝 Description

A modern peer-to-peer implementation of the classic Tic-Tac-Toe game for two players. Play online by creating a new game or joining an existing match directly through your browser - no server, no downloads, just pure fun!

### ✨ Features

- **🎯 Real-time Gameplay** - Instant synchronization between players
- **🔗 P2P Connection** - Direct peer-to-peer connection via Firebase Realtime Database
- **💬 Built-in Chat** - Communicate with your opponent during the game
- **🎨 Cyberpunk Design** - Modern neon-themed UI with smooth animations
- **📱 Responsive Layout** - Works perfectly on desktop and mobile devices
- **🔄 Quick Restart** - Start a new game without refreshing the page
- **🌐 Share & Play** - Simply share a link to invite friends
- **⚡ No Registration** - Jump straight into the game

### 🚀 How to Play

1. Visit the [demo page](https://dneese.github.io/P2P-tic-tac-toe/)
2. Click **"Create Game"** and share the generated link with a friend
3. OR enter a game ID to join an existing game
4. Wait for both players to connect
5. Enjoy the game!

### 🛠️ Technologies

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Styling:** Custom CSS with cyberpunk theme, Google Fonts (Orbitron)
- **Backend:** Firebase Realtime Database
- **Architecture:** Real-time peer-to-peer synchronization
- **Deployment:** GitHub Pages

### 📦 Installation & Setup

#### For Players
No installation needed! Just visit the live demo link.

#### For Developers

1. Clone the repository:
```bash
git clone https://github.com/dneese/P2P-tic-tac-toe.git
cd P2P-tic-tac-toe
```

2. Set up Firebase:
   - Create a project at [Firebase Console](https://console.firebase.google.com/)
   - Enable Realtime Database
   - Copy your Firebase config and replace it in `index.html`

3. Open `index.html` in your browser or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx http-server
```

4. Navigate to `http://localhost:8000`

### 🔧 Firebase Configuration

Replace the Firebase config in `index.html` with your own:

```javascript
const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_PROJECT.firebaseapp.com",
    databaseURL: "https://YOUR_PROJECT.firebasedatabase.app",
    projectId: "YOUR_PROJECT_ID",
    storageBucket: "YOUR_PROJECT.appspot.com",
    messagingSenderId: "YOUR_SENDER_ID",
    appId: "YOUR_APP_ID"
};
```

### 🎯 Game Rules

- Players take turns placing X's and O's on a 3x3 grid
- First player to get 3 marks in a row (horizontal, vertical, or diagonal) wins
- If all 9 squares are filled without a winner, the game is a draw
- Player 1 (host) always plays as X and goes first
- Player 2 (guest) plays as O

### 🗺️ Roadmap

- [ ] Add game statistics and score tracking
- [ ] Implement sound effects
- [ ] Add customizable themes
- [ ] Support for tournament mode
- [ ] Add AI opponent option
- [ ] Implement reconnection handling
- [ ] Add emoji reactions
- [ ] Create mobile app version

### 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### 👨‍💻 Author

**dneese**
- GitHub: [@dneese](https://github.com/dneese)
- Project Link: [https://github.com/dneese/P2P-tic-tac-toe](https://github.com/dneese/P2P-tic-tac-toe)

### 🙏 Acknowledgments

- Font: [Orbitron by Google Fonts](https://fonts.google.com/specimen/Orbitron)
- Backend: [Firebase Realtime Database](https://firebase.google.com/)
- Hosting: [GitHub Pages](https://pages.github.com/)

---

## Українська

### 🌟 Жива Демонстрація
**Грати зараз:** [https://dneese.github.io/P2P-tic-tac-toe/](https://dneese.github.io/P2P-tic-tac-toe/)

![Скріншот гри](screenshot.png)

### 📝 Опис

Сучасна P2P (peer-to-peer) реалізація класичної гри "Хрестики-Нолики" для двох гравців. Грайте онлайн, створюючи нові ігри або приєднуючись до існуючих партій напряму через браузер - без серверів, без завантажень, просто чиста гра!

### ✨ Можливості

- **🎯 Гра в реальному часі** - Миттєва синхронізація між гравцями
- **🔗 P2P з'єднання** - Пряме peer-to-peer з'єднання через Firebase Realtime Database
- **💬 Вбудований чат** - Спілкуйтесь з опонентом під час гри
- **🎨 Кіберпанк дизайн** - Сучасний неоновий інтерфейс з плавними анімаціями
- **📱 Адаптивний макет** - Ідеально працює на десктопі та мобільних пристроях
- **🔄 Швидкий перезапуск** - Почніть нову гру без оновлення сторінки
- **🌐 Поділись та грай** - Просто поділіться посиланням, щоб запросити друзів
- **⚡ Без реєстрації** - Переходьте одразу до гри

### 🚀 Як Грати

1. Відвідайте [демо-сторінку](https://dneese.github.io/P2P-tic-tac-toe/)
2. Натисніть **"Створити гру"** і поділіться згенерованим посиланням з другом
3. АБО введіть ID гри, щоб приєднатися до існуючої гри
4. Дочекайтеся підключення обох гравців
5. Насолоджуйтеся грою!

### 🛠️ Технології

- **Фронтенд:** HTML5, CSS3, JavaScript (Vanilla)
- **Стилізація:** Власний CSS з кіберпанк темою, Google Fonts (Orbitron)
- **Бекенд:** Firebase Realtime Database
- **Архітектура:** Синхронізація peer-to-peer в реальному часі
- **Деплой:** GitHub Pages

### 📦 Встановлення та Налаштування

#### Для Гравців
Встановлення не потрібне! Просто відвідайте посилання на демо.

#### Для Розробників

1. Клонуйте репозиторій:
```bash
git clone https://github.com/dneese/P2P-tic-tac-toe.git
cd P2P-tic-tac-toe
```

2. Налаштуйте Firebase:
   - Створіть проект в [Firebase Console](https://console.firebase.google.com/)
   - Увімкніть Realtime Database
   - Скопіюйте вашу Firebase конфігурацію та замініть її в `index.html`

3. Відкрийте `index.html` у браузері або використайте локальний сервер:
```bash
# Використовуючи Python 3
python -m http.server 8000

# Використовуючи Node.js
npx http-server
```

4. Перейдіть до `http://localhost:8000`

### 🔧 Конфігурація Firebase

Замініть Firebase конфігурацію в `index.html` на вашу власну:

```javascript
const firebaseConfig = {
    apiKey: "ВАШ_API_KEY",
    authDomain: "ВАШ_ПРОЕКТ.firebaseapp.com",
    databaseURL: "https://ВАШ_ПРОЕКТ.firebasedatabase.app",
    projectId: "ВАШ_ID_ПРОЕКТУ",
    storageBucket: "ВАШ_ПРОЕКТ.appspot.com",
    messagingSenderId: "ВАШ_SENDER_ID",
    appId: "ВАШ_APP_ID"
};
```

### 🎯 Правила Гри

- Гравці по черзі ставлять X та O на сітці 3x3
- Перший гравець, який отримає 3 позначки в ряд (горизонтально, вертикально або діагонально) виграє
- Якщо всі 9 клітинок заповнені без переможця - нічия
- Гравець 1 (хост) завжди грає за X і ходить першим
- Гравець 2 (гість) грає за O

### 🗺️ Дорожня Карта

- [ ] Додати статистику ігор та відстеження рахунку
- [ ] Реалізувати звукові ефекти
- [ ] Додати налаштовувані теми
- [ ] Підтримка турнірного режиму
- [ ] Додати опцію гри проти ШІ
- [ ] Реалізувати обробку переподключення
- [ ] Додати емодзі реакції
- [ ] Створити мобільну версію додатку

### 🤝 Внесок у Проект

Внески вітаються! Будь ласка, не соромтеся надсилати Pull Request. Для значних змін спочатку відкрийте issue, щоб обговорити, що ви хотіли б змінити.

1. Зробіть Fork репозиторію
2. Створіть вашу гілку функціоналу (`git checkout -b feature/ДивовижнаФункція`)
3. Закомітьте ваші зміни (`git commit -m 'Додати якусь ДивовижнуФункцію'`)
4. Відправте в гілку (`git push origin feature/ДивовижнаФункція`)
5. Відкрийте Pull Request

### 📄 Ліцензія

Цей проект ліцензовано під MIT License - дивіться файл [LICENSE](LICENSE) для деталей.

### 👨‍💻 Автор

**dneese**
- GitHub: [@dneese](https://github.com/dneese)
- Посилання на проект: [https://github.com/dneese/P2P-tic-tac-toe](https://github.com/dneese/P2P-tic-tac-toe)

### 🙏 Подяки

- Шрифт: [Orbitron від Google Fonts](https://fonts.google.com/specimen/Orbitron)
- Бекенд: [Firebase Realtime Database](https://firebase.google.com/)
- Хостинг: [GitHub Pages](https://pages.github.com/)

---

<div align="center">
  
### ⭐ Якщо вам сподобався цей проект, поставте зірочку!
### ⭐ If you liked this project, give it a star!

Made with ❤️ by [dneese](https://github.com/dneese)

</div>