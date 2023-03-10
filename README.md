# goit-markup-hw-05

Позиционирование
Блочная модель
Типографика
Оформление
Анимация
Разное

.selector-item {
  /* Позиционирование */
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 100;

  /* Блочная модель */
  display: inline-block;
  float: left;
  width: 150px;
  height: 150px;
  margin: 25px;
  padding: 25px;

  /* Типографика */
  font: normal 13px/1.5 "Helvetica", sans-serif;
  font-style: normal;
  font-size: 13px;
  line-height: 1.5;
  font-family: "Helvetica", sans-serif;
  text-align: start;

  /* Оформление */
  color: #999999;
  background-color: #e3e3e3;
  border: 1px solid #333333;
  border-radius: 5px;
  opacity: 1;

  /* Анимация */
  transition: all 0.8s;

  /* Разное */
  will-change: auto;
}