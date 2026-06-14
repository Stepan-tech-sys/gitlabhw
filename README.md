# Домашнее задание к занятию "`Gitlab`" - `Лопатников Степан`


---

### Задание 1


`При необходимости прикрепитe сюда скриншоты
![Название скриншота 1](https://github.com/Stepan-tech-sys/screenshots/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202026-06-14%2021-07-55.png)(https://github.com/Stepan-tech-sys/screenshots/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202026-06-14%2021-07-17.png)`


---

### Задание 2

```
Поле для вставки кода...
stages:
  - test
  - build

test:
  stage: test
  image: golang:1.17
  script:
   - go test .

build:
  stage: build
  image: docker:latest
  script:
   - docker build .
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота 2](https://github.com/Stepan-tech-sys/screenshots/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202026-06-14%2022-48-46.png)`


---

