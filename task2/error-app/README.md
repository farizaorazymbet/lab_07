# Lab 7.2 — Error Handling with Error Boundary

## Қысқаша түсіндіру
Бұл жұмыста React қосымшасында Error Boundary қолданылды.

- ErrorBoundary — class компонент.
- getDerivedStateFromError әдісі арқылы қате ұсталады.
- Қате болған жағдайда fallback UI көрсетіледі.
- Retry батырмасы арқылы қайта жүктеу мүмкіндігі бар.

Error Boundary қосымша crash болмауын қамтамасыз етеді.

## Жоба құрылымы
task2/error-app/
│
├── src/
│ ├── pages/
│ ├── components/
│ │ ├── ErrorBoundary.tsx
│ │ └── ErrorFallback.tsx
│ ├── App.tsx
│ └── main.tsx

## Қалай іске қосылады
1. Папкаға кіру:
cd task2/error-app

2. Тәуелділіктерді орнату:
npm install

3. Іске қосу:
npm run dev

4. Браузерде ашу:
http://localhost:5173