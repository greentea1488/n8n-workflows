# n8n Workflows Collection

Коллекция рабочих и продвинутых воркфлоу для **n8n**, собранных из реальных проектов: Telegram‑боты, мультимодальные ассистенты, RAG, интеграции с Bitrix24, финансы и автоматизация рутины.

Каждый workflow — это:

- Полностью готовый JSON-шаблон для импорта в n8n
- Краткий README с описанием логики и требований
- Примеры интеграций с OpenAI, Telegram, Google Sheets, Bitrix24, Qdrant, MCP и др.

## Список воркфлоу

1. **Multi‑Modal Telegram Chatbot**  
   Понимает текст, голос, фото, PDF и таблицы.  
   Папка: `multi-modal-chatbot/`

2. **BudgetBot (Telegram + Voice + Sheets + Gmail)**  
   Бот для ведения бюджета: принимает текст/голос, конвертирует, помогает управлять расходами.  
   Папка: `budget-bot/`

3. **Budget Weekly Reporter**  
   Автоматический недельный отчёт по бюджету из Google Sheets.  
   Папка: `budget-weekly-reporter/`

4. **AICEX Sales Assistant (Telegram)**  
   Продающий ассистент с памятью для онлайн‑продуктов.  
   Папка: `aicex-sales-assistant/`

5. **RAG Assistant (Qdrant + MCP + OpenAI)**  
   RAG‑слой с загрузкой PDF через форму и поиском по базе знаний.  
   Папка: `rag-assistant/`

6. **Hook Generator Client (LLM + MCP)**  
   Генератор маркетинговых хуков и креативов с использованием LLM и MCP‑инструментов.  
   Папка: `hook-generator-client/`

7. **neuroCRM Legal PDF Automation (Bitrix24 → PDF)**  
   Авто‑генерация юридических претензий по данным сделок Bitrix24 и формирование PDF.  
   Папка: `neurocrm-legal-pdf/`

---

## Как импортировать workflow в n8n

1. Откройте ваш инстанс **n8n**  
2. Нажмите **Import from File**  
3. Выберите соответствующий `workflow.json` из нужной папки  
4. Обновите креды (Telegram, Google, OpenAI, Bitrix24, Qdrant и др.), IDs ботов, документов и таблиц  
5. Активируйте workflow
