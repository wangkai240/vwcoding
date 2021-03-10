---
hide:
  - toc
disqus: https-mqb-readthedocs-io
---

# Прошивки для камеры ассистентов

Для полноценной работы камеры ассистентов нужна правильная прошивка и параметрия к ней.  
Камеры могут быть 3 вариантов:  

* 5Q0... - MFK1 (Lane Assist, Sign Assist, DLA)  
* 3Q0/3QD... - MFK2 (Lane Assist, Sign Assist, Traffic Jam Assist, DLA)  
* 2Q0... - MFK3 (Lane Assist, Sign Assist, Traffic Jam Assist, Pedestrian Assist, DLA)  

### Прошивки для камер вида MFK2

!!! warning "Важно!"
    Порядок обновления должен быть следующим: G → H → L → T → Q → R → S  
    Изменение этого порядка в обратном порядке повредит вашу камеру

Поколение 4:  

| ID оборудования               | Прошивка                                        | Параметрия<br/>(ODIS XML)                           | Примечания                       |
| ----------------------------- |:-----------------------------------------------:|:---------------------------------------------------:|:--------------------------------:|
| FL_3Q0980654_0920_3Q0980654S  | [(Скачать)](../firmwares/FL_3Q0980654_0920.frf) | [(Скачать)](../firmwares/A5_3Q0980654S_BW2_STA.xml) | Не рекомендуется для Tiguan 2G.<br/>Существуют проблемы с удержанием в полосе |
| FL_3Q0980654_0460_3Q0980654R  ||||
| FL_3Q0980654_0881_3Q0980654Q  ||||
| FL_3Q0980654_0451_3Q0980654M  ||||

Поколение 3:  

| ID оборудования               | Прошивка                                        | Параметрия<br/>(ODIS XML)                               | Примечания                       |
| ----------------------------- |:-----------------------------------------------:|:-------------------------------------------------------:|:--------------------------------:|
| FL_3Q0980654_0611_3QD980654T  ||| Прошивка для Tiguan 2G от модельного ряда 2020 года |
| FL_3Q0980654_0610_3QD980654L  | [(Скачать)](../firmwares/FL_3Q0980654_0610.frf) | [(Скачать)](../firmwares/A5_3Q0980654L_TJA_653_mod.xml) ||
| FL_3QD980654_1611_3QD980654A  ||||

Поколение 2:  

| ID оборудования               | Прошивка                                        | Параметрия<br/>(ODIS XML)                               | Примечания                       |
| ----------------------------- |:-----------------------------------------------:|:-------------------------------------------------------:|:--------------------------------:|
| FL_3Q0980654_0272_3QD980654H  | [(Скачать)](../firmwares/FL_3Q0980654_0272.frf) |||
| FL_3QD980654_1272_3QD980654   ||||
| FL_3Q0980654_0231_3QD980654G  ||||
| FL_3Q0980654_0220_3QD980654F  ||||

Поколение 1:  

| ID оборудования               | Прошивка                                        | Параметрия<br/>(ODIS XML)                               | Примечания                       |
| ----------------------------- |:-----------------------------------------------:|:-------------------------------------------------------:|:--------------------------------:|
| FL_3Q0980654_0024_3Q0980654D  ||||
| FL_3Q0980654_0010_3Q0980654C  ||||