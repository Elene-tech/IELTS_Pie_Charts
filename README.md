# Module 2 · Pie Charts — інструкція з розміщення

Крок 1 — GitHub (5 хв)
1. Зайди на github.com → увійди → натисни «New repository».
2. Назва: `ielts-pie-charts` (без пробілів). Постав галочку «Public». Створи.
3. Натисни «uploading an existing file» → перетягни ВСІ файли з папки модуля
   (6 HTML-файлів) → «Commit changes».

Крок 2 — Vercel (3 хв)
1. Зайди на vercel.com → увійди через GitHub.
2. «Add New…» → «Project» → знайди репозиторій `ielts-pie-charts` → «Import».
3. Нічого не змінюй у налаштуваннях → «Deploy». Через 30 секунд сайт готовий.
4. Посилання буде виду: https://ielts-pie-charts-xxx.vercel.app

Крок 3 — Kwiga (2 хв)
Встав у блок «HTML-код» одну з двох опцій:

Варіант А — весь модуль однією сторінкою (рекомендовано):
<iframe src="https://ТВОЄ-ПОСИЛАННЯ.vercel.app/index.html"
        width="100%" height="1200"
        style="width:100% !important; border:none; border-radius:12px;"
        loading="lazy"></iframe>

Варіант Б — окремі тренажери (можна вставляти свої пояснення між ними):
<iframe src="https://ТВОЄ-ПОСИЛАННЯ.vercel.app/01-pie-overview-trainer.html" width="100%" height="1200" style="width:100% !important; border:none; border-radius:12px;"></iframe>
<iframe src="https://ТВОЄ-ПОСИЛАННЯ.vercel.app/02-pie-grouping-trainer.html" width="100%" height="1200" style="width:100% !important; border:none; border-radius:12px;"></iframe>
<iframe src="https://ТВОЄ-ПОСИЛАННЯ.vercel.app/03-pie-parts-trainer.html" width="100%" height="1200" style="width:100% !important; border:none; border-radius:12px;"></iframe>
<iframe src="https://ТВОЄ-ПОСИЛАННЯ.vercel.app/04-pie-final-tasks.html" width="100%" height="1200" style="width:100% !important; border:none; border-radius:12px;"></iframe>
<iframe src="https://ТВОЄ-ПОСИЛАННЯ.vercel.app/05-pie-vocabulary.html" width="100%" height="1200" style="width:100% !important; border:none; border-radius:12px;"></iframe>

Порядок уроку: твоє відео (звичайний блок Kwiga) → iframe → за бажанням пояснення.

Як оновити файл
- GitHub → відкрий файл → олівець (Edit) → встав новий код → «Commit changes».
  Vercel оновить сайт сам за ~1 хвилину.

Англійська версія (на потім)
- Тексти інтерфейсу зібрані в блоці `const UI`/статичних рядках на початку файлів —
  переклад цих рядків = англійська версія без зміни коду.
