# React Practice

این ریپو ادامه‌ی مسیر یادگیری فرانت‌اند منه، بعد از تکمیل [frontend-practice](https://github.com/mousaamiri/frontend-practice) (HTML/CSS/JS خالص، بدون فریم‌ورک).

پس‌زمینه‌ی من Backend (.NET/C#, Clean Architecture, DDD, CQRS) هست.

---

## اصول این ریپو

- **اول JS خالص، بعد TypeScript.** تا وقتی مفاهیم خود React (component, state, props, re-render) جا نیفتاده، TS اضافه نمی‌شه — چون قاطی کردن دو مفهوم جدید همزمان، ردیابی منبع باگ رو غیرممکن می‌کنه.
- **هر تمرین توی پوشه‌ی خودش**، با یه پروژه‌ی مستقل Vite (`npm create vite@latest <folder-name> -- --template react`).
- هر commit پیام واضح داره (`add: first counter component`)

---

## نقشه راه

### 📁 01 - React Basics
JSX, components, props, state, event handling, conditional rendering, list rendering (`key`)

- [ ] Counter Component — اولین تماس با `useState`
- [ ] Todo List (بدون فریم‌ورک state management) — همون Todo قدیمی ولی این‌بار React خودش re-render رو مدیریت می‌کنه
- [ ] Props Drilling Demo — یه کامپوننت چندلایه که props رو پاس می‌ده، برای حس کردن مشکلی که Context قراره حلش کنه

### 📁 02 - Hooks Deep Dive
`useEffect`, `useRef`, `useMemo`, `useCallback`, custom hooks

- [ ] Fetch با `useEffect` (و مدیریت cleanup/race condition)
- [ ] Debounced Search Input (`useRef` + `useEffect` ترکیبی)
- [ ] Custom Hook: `useLocalStorage`
- [ ] چرا `useMemo`/`useCallback` همیشه لازم نیستن (تمرینی که نشون بده overuse بده)

### 📁 03 - Routing
React Router: nested routes, dynamic params, protected routes

- [ ] چند صفحه‌ی ساده با `react-router-dom`
- [ ] Dynamic route (`/product/:id`)
- [ ] Protected route ساده (شبیه‌سازی auth guard)

### 📁 04 - Forms & Data
Controlled inputs, validation, فچ کردن از یه API واقعی

- [ ] فرم ثبت‌نام با validation دستی (بدون کتابخانه)
- [ ] همون فرم با React Hook Form
- [ ] CRUD کامل روی یه API عمومی (fetch, loading, error states)

### 📁 05 - State Management
Context API در برابر ابزارهای خارجی

- [ ] Context API برای theme/auth ساده
- [ ] وقتی Context کافی نیست — مقدمه‌ای بر Zustand یا Redux Toolkit (تصمیم بعداً گرفته می‌شه)

### 📁 06 - TypeScript Migration
بازنویسی یکی از پروژه‌های قبلی با TS

- [ ] یکی از پروژه‌های فصل ۱ یا ۲ رو با TypeScript از نو بنویس
- [ ] typing برای props, state, API responses

### 📁 07 - Mini Full Project
ترکیب همه‌چیز: routing + fetch + state management + forms

- [ ] یک پروژه‌ی کامل کوچیک (جزئیات بعداً مشخص می‌شه — احتمالاً چیزی که با بک‌اند خودم هم قابل اتصاله)

---

## ریپوی مرتبط

مسیر قبلی (HTML/CSS/JS خالص): [frontend-practice](https://github.com/mousaamiri/frontend-practice)
