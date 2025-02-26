[![Build status](https://ci.appveyor.com/api/projects/status/iut27g3ytj9jdg6q?svg=true)](https://ci.appveyor.com/project/MShapaev/ahj-code-forms)

Правила сдачи задания:
1. **Важно**: в рамках этого ДЗ вы можете использовать любой пакетный менеджер.
2. Всё, включая картинки и стили, должно собираться через Webpack и выкладываться на GitHub Pages через AppVeyor.
3. В README.md должен быть размещён бейджик сборки и ссылка на GitHub Pages.
4. В качестве результата присылайте проверяющему ссылки на ваши GitHub-проекты.

---

### Popovers

#### Легенда

Есть замечательный фреймворк Bootstrap, в котором реализовано достаточно много интересных виджетов с использованием jQuery. Но, как говорят современные и модные программисты, «jQuery не нужен», поэтому вам нужно реализовать такой же виджет на чистом JS.

#### Описание

Вот так должен выглядеть виджет в целом. Будем считать, что виджет всегда должен показываться сверху.

![](./src/img/Popovers.png)


У popover обязательно должно быть название и текст. Центрироваться он должен по горизонтали относительно элемента, который вызвал popover.

Не забудьте написать автотест на взаимодействие с DOM на базе Puppeteer или JSDOM, на ваш выбор.

**Подсказка**: [страница, на которой можно подсмотреть реализацию](https://getbootstrap.com/docs/4.3/components/popovers/). Но мы пока не проходили `translate`, `translate3d`, поэтому делайте позиционирование в px.
