# YandexResumeSender

**Отправка своего резюме в Яндекс в автоматическом режиме — потому что автоматизация делает вашу жизнь проще (а может, и нет).**

---

### Описание проекта

Этот скрипт создан для тех, кто устал вручную отправлять свое резюме на вакансии Яндекса. Теперь вы можете потратить свое время на что-то действительно важное, например, на размышления о том, почему вам все еще не ответили.

С помощью этой программы вы сможете:
- Автоматически открывать ссылки на вакансии.
- Прокручивать страницу до нужного элемента (если повезет).
- Кликать на формы с кнопками и загружать файл с резюме.
- Получать ошибки, которые заставят вас задуматься о смысле жизни.

---

### Установка

1. Склонируйте репозиторий:
   ```bash
   git clone https://github.com/D1m7asis/YandexResumeSender.git
   cd YandexResumeSender
   ```
   *(Если вы не знаете, как это сделать, возможно, вам стоит подумать о другой карьере.)*

2. Установите зависимости:
   ```bash
   pip install -r requirements.txt
   ```
   *(Если у вас нет Python, то... ну, вы поняли.)*

3. Создайте файл `links.txt` и добавьте туда ссылки на вакансии, по одной на строку:
   ```
   https://yandex.ru/jobs/vacancies/razrabotchik-na-russkom
   https://yandex.ru/jobs/vacancies/razrabotchik-na-angliyskom
   ```
   *(Пожалуйста, не забудьте проверить, что ссылки работают. Я не стану это делать за вас.)*

4. Закиньте свое резюме в корневую папку проекта и убедитесь, что его имя совпадает с тем, что указано в коде:
   ```
   CV.pdf
   ```
   *(Если ваше резюме называется иначе, то... ну, вы догадались.)*

---

### Использование

Запустите скрипт:
```bash
python main.py
```

Теперь программа будет делать вид, что она работает. Если что-то пойдет не так (а это почти наверняка произойдет), вы получите красивую ошибку в консоль:
```
Ошибка при обработке ссылки https://yandex.ru/jobs/vacancies/razrabotchik-na-kitayskom: Message: no such element: Unable to locate element...
```

*(Не волнуйтесь, это просто значит, что вы должны сами дописать за меня код, или, может быть, попробовать снова завтра.)*

---

### Особенности

- **Умный скроллинг:** Программа знает, как прокрутить страницу до нужного элемента. Почти всегда. Иногда она просто решает, что этого делать не стоит.
- **Обработка iframe:** Мы даже учли, что Яндекс любит прятать свои элементы в iframe. Почти как ваши шансы на собеседование.
- **Логирование ошибок:** Если что-то сломается, вы узнаете об этом. Возможно, это будет единственным полезным результатом работы программы.

---

### FAQ

**Q:** Почему программа не работает?  
**A:** Потому что Яндекс не хочет, чтобы вы автоматизировали отправку резюме. Но вы же дмогли догадатсья, что это было бы слишком просто, правда?

**Q:** Что делать, если я получил ошибку?  
**A:** Попробуйте снова. Если не помогло, попробуйте снова. Если опять не помогло, возможно, это знак свыше.

**Q:** Можно ли использовать этот скрипт для других сайтов?  
**A:** Теоретически да. Практически — скорее всего, нет.

---

### Лицензия

MIT License. Делайте с этим кодом что хотите. Только не жалуйтесь, если он сломается.

---

### Заключение

YandexResumeSender — это ваш личный помощник в борьбе с бюрократией и однообразием. Или, возможно, просто еще один способ осознать, что автоматизация не всегда спасает мир.

Удачи в поиске работы! *(Вы ее точно заслуживаете. Может быть.)*
