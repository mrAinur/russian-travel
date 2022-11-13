# Проект: Путешествие по России
В данном проекте вы увидите многие интересные места России.
## Также вы познакомитесь с возможностью добраться до Байкала "На собаках"
Это один интересный метод путешествовать, в котором вы наверняка встретите множество приключений и новых знакомых.
## Узнаете самые интересные места нашей Родины
:white_check_mark: Куршская коса;
:white_check_mark: Кольский;
:white_check_mark: Алтай;
:white_check_mark: Зимний Байкал;
:white_check_mark: Карелия.
## Проект сделан при помощи технологий адаптивной вёрстки и флексбокс инструментов
:white_check_mark: Примеры технологий адаптивной вёрстки:
```CSS
@media screen and (max-width: 1279px) {
  .photo-grid {
    max-width: 928px;
    min-height: 942px;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(4, 1fr);
    gap: 14px;
  }
}
@media screen and (max-width: 1040px) {
  .photo-grid {
    max-width: 720px;
    min-height: 1664px;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(6, 1fr);
    gap: 16px;
  }
}
@media screen and (max-width: 784px) {
  .photo-grid {
    max-width: 288px;
    min-height: 2724px;
    grid-template-columns: repeat(1, 1fr);
    grid-template-rows: repeat(12, 1fr);
    gap: 12px;
    margin: 64px auto 0 auto;
  }
}
```
:white_check_mark: Примеры применения грид - элементов:
```CSS
.place {
  display: grid;
  grid-template-columns: repeat(fit-content, (2, 1fr));
  grid-template-rows: repeat(fit-content, (2, 1fr));
  grid-template-areas:
    "title link"
    "img paragraph";
  gap: 48px 40px;
  padding-bottom: 80px;
}
```
## Данный сайт поможет вам больше узнать как и России, так и о технологии адаптивной вёрстки
Путешествуйте и наслаждайтесь жизнью!
### Ссылка на сайт (gh-pages)
 https://mrainur.github.io/russian-travel/
