# Lab 7.1 — Code Splitting with React.lazy() және Suspense

## Қысқаша түсіндіру

Бұл жұмыста React қосымшасында code splitting техникасы қолданылды.  

- `React.lazy()` арқылы беттер динамикалық түрде жүктеледі.
- `Suspense` компоненті lazy бет жүктелгенше fallback (spinner) көрсетеді.
- Home беті бірден жүктеледі.
- Dashboard, Settings, Profile беттері lazy load арқылы жүктеледі.

Бұл тәсіл қосымшаның бастапқы жүктелу уақытын азайтады.
## Жоба құрылымы
task1/lazy-app/
│
├── src/
│ ├── pages/
│ ├── components/
│ ├── App.tsx
│ └── main.tsx

## Қалай іске қосылады
1. Папкаға кіру:
cd task1/lazy-app

2. Тәуелділіктерді орнату:
npm install
3. Іске қосу:
npm run dev
4. Браузерде ашу:
http://localhost:5173