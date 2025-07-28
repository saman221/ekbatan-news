ekbatan-news/
├── index.html          ← صفحه اصلی سایت
├── all-news.html       ← نمایش تمام خبرها
├── admin.html          ← پنل مدیریت (افزودن خبر جدید)
├── style.css           ← استایل‌ها
├── script.js           ← اسکریپت‌های فرانت
├── backend/
│   └── main.py         ← سرور FastAPI
└── supabase_schema.sql ← طرح جدول خبرها
uvicorn main:app --reload
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
