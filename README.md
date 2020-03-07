# dif_bw_abstr_class_and_interface

Когда стоит применять интерфейсы, а когда абстрактные классы?

Ответ:
  Абстрактный класс - это более широкое понятие. Можно даже сказать интерфейс, "частный случай" абстрактого класса.
  
  Стоит использовать интерфейс, когда один класс хочет дать возможность другому доступа только к некоторым своим методам (но не открыть свои свойства и другие private методы). 
  
  Стоит использовать абстрактный класс, когда им можно описать семейство классов, у которых много общего. Если в данном случае использовать интерфейс, будет больше дублирования кода. Например, есть общие свойства для всего семейства классов, разумно их сразу создать в абстрактном классе, а так же общие для всех методы и их логику. 
