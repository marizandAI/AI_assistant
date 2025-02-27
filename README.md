# ИИ-ассистент образовательного проекта

## Описание проекта

Этот проект представляет собой интеллектуального ассистента, созданного специально для образовательных организаций. Ассистент способен эффективно взаимодействовать с пользователями, предоставляя информацию, отвечая на вопросы и помогая в организации учебного процесса.

---

## Функционал

### 1. **Осмысленное ведение диалога**
   - Ассистент использует передовые технологии нейросетей для поддержания естественного и осмысленного диалога с пользователем.
   - Понимает контекст разговора и адаптируется к запросам клиента.

### 2. **Ответы на вопросы по базе знаний**
   - Интегрирована база знаний, содержащая актуальную информацию об образовательных программах, курсах, преподавателях и других важных аспектах.
   - Ассистент может быстро находить и предоставлять точные ответы на вопросы пользователей.

### 3. **Запись на пробное занятие**
   - Клиенты могут записаться на пробное занятие через интерфейс ассистента.
   - Процесс записи прост и интуитивно понятен.

### 4. **Добавление встречи в Google Календарь**
   - После записи на пробное занятие ассистент автоматически создает событие в Google Календаре как для клиента, так и для образовательной организации.
   - Это обеспечивает удобство и минимизирует вероятность пропуска встречи.

---

## Используемые сервисы

### 1. **Qwen**
   - **Назначение**: Создание системного промпта и базы знаний.
   - **Особенности**:
     - Qwen позволяет гибко настраивать поведение ассистента, определяя правила общения и области знаний.
     - База знаний регулярно обновляется, чтобы оставаться релевантной и полезной.

### 2. **Savvy (https://suvvy.ai/)**
   - **Назначение**: Платформа для создания и управления ИИ-ассистентом.
   - **Особенности**:
     - Простой и интуитивный интерфейс для настройки функционала ассистента.
     - Возможность интеграции с различными внешними сервисами, включая Google Календарь.

---

## Как это работает

1. **Инициация диалога**:
   - Пользователь начинает общение с ассистентом через чат или другой доступный канал связи.

2. **Обработка запроса**:
   - Ассистент анализирует сообщение пользователя, опираясь на системный промпт и базу знаний.

3. **Предоставление ответа**:
   - Если вопрос связан с информацией из базы знаний, ассистент предоставляет точный и релевантный ответ.
   - В случае необходимости записи на пробное занятие ассистент запрашивает необходимые данные (например, дату и время) и создает соответствующее событие в Google Календаре.

4. **Подтверждение действия**:
   - После завершения операции (запись на занятие, добавление события в календарь), ассистент отправляет подтверждение пользователю.

---

## Преимущества использования

- **Экономия времени**: Автоматизация процессов записи и планирования высвобождает время сотрудников образовательной организации.
- **Улучшение клиентского опыта**: Пользователи получают быстрые и точные ответы на свои вопросы, что повышает удовлетворенность.
- **Масштабируемость**: Ассистент может обслуживать большое количество пользователей одновременно без потери качества обслуживания.

---

## Технические детали

### Стек технологий:
- **Языки программирования**: Python (для настройки интеграций).
- **API**: API Qwen, API Savvy, Google Calendar API.
- **База данных**: Хранение информации о пользователях и их записях на занятия.

### Архитектура:
- **Фронтенд**: Интерфейс для взаимодействия с пользователем.
- **Бэкенд**: Обработка запросов, работа с API и базой данных.
- **Интеграция**: Соединение всех компонентов в единую систему.

---

## Руководство по установке

1. **Клонирование репозитория**:
   ```bash
   git clone https://github.com/your-repository-url.git
   ```

2. **Настройка окружения**:
   - Установите необходимые зависимости из файла `requirements.txt`:
     ```bash
     pip install -r requirements.txt
     ```

3. **Настройка API ключей**:
   - Получите API ключи для Qwen, Savvy и Google Calendar.
   - Добавьте их в файл `.env`.

4. **Запуск приложения**:
   ```bash
   python app.py
   ```

---

## Дальнейшие планы развития

- Расширение базы знаний для охвата большего количества тем.
- Добавление мультиязычной поддержки для работы с международными клиентами.
- Интеграция с дополнительными сервисами, такими как CRM-системы.

---

## Контакты

Если у вас есть вопросы или предложения по улучшению проекта, свяжитесь с нами:

- Email: marizand2018@gmail.com

---

## Лицензия

Проект распространяется под лицензией [MIT](LICENSE).
