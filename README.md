# Keepsake — landing page

Адаптивний односторінковий лендинг дизайн-агенції Keepsake (лабораторна робота №7, завдання 4).

**Демо:** _додати посилання на GitHub Pages_

## Технології та рішення
- Чистий HTML5 і CSS, без фреймворків і UI-бібліотек
- Mobile first: базові стилі від 320 px, далі `@media (min-width: 768px)` і `(min-width: 1280px)`
- Усі кольори, шрифти й відступи — CSS-змінні в `:root`
- Flexbox для розкладки, CSS Grid для сітки портфоліо (`aspect-ratio` для карток)
- Шрифти Google Fonts: Oswald, Open Sans, Dancing Script (`display=swap`)
- Іконки — інлайн-SVG
- Мобільне меню без JS (checkbox + `:checked`), фільтр портфоліо через `:checked ~`
- Ховер/фокус карток (`:hover`, `:focus-visible`, `:focus-within`)
- Форма підписки: HTML-валідація, стани error/success (невеликий скрипт лише для повідомлення про успіх)
- Fixed header і кнопка «вгору»
# landing-keepsake
