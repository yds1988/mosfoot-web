# 🌐 MosFoot Web Interface
Статический веб-интерфейс для отображения статистики футбольного сообщества MosFoot

## 🔧 КАК НАСТРОИТЬ САЙТ (ОБЯЗАТЕЛЬНО ПРОЧТИТЕ!)

### ШАГ 1: Получите данные из Supabase
1. Откройте панель управления Supabase
2. Нажмите на иконку шестерёнки ⚙️ (Project Settings)
3. Выберите "API" в левом меню
4. Скопируйте:
   - **Project URL** (начинается с `https://`)
   - **anon** ключ (длинная строка)

### ШАГ 2: Отредактируйте файл index.html
1. Откройте файл `index.html` в Блокноте
2. НАЙДИТЕ ЭТИ СТРОКИ (примерно строка 440):
   ```javascript
   const SUPABASE_URL = 'https://xwkvyzwvdhswlqnhhpns.supabase.co';
   const SUPABASE_KEY = 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Inh3a3Z5end2ZGhzd2xxbmhocG5zIiwicm9sZSI6ImFub24iLCJpYXQiOjE3Njk4ODM2NzIsImV4cCI6MjA4NTQ1OTY3Mn0.T6bMxkJZoGGNR_RrgfVvHy0Irx0ccWMckvnZacSsrlM';