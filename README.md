# Домашнее задание к занятию 11 «Teamcity» - Бодарев В.В.

---

Подготовим виртуалки 

![image alt](https://github.com/vasionxxx/ans/blob/main/8.jpg)

---

Создадим новый проект в teamcity на основе fork, сделаем autodetect конфигурации и запустим первую сборку

![image alt](https://github.com/vasionxxx/ans/blob/main/81.jpg)


---

Поменяем условия сборки: если сборка по ветке master, то должен происходит mvn clean deploy, иначе mvn clean test

![image alt](https://github.com/vasionxxx/ans/blob/main/82.jpg)

---

Запустим сборку по master, убедимся, что всё прошло успешно и артефакт появился в nexus

![image alt](https://github.com/vasionxxx/ans/blob/main/83.jpg)

---

Дополним тест для нового метода на поиск слова hunter в новой реплике.

public String sayHunterwho() {
	    return "Who is hunter?";
	}

Тест сборки по ветке feature/add_reply

![image alt](https://github.com/vasionxxx/ans/blob/main/84.jpg)

---

В путь артефактов добавим

target/*.jar => build-artifacts

![image alt](https://github.com/vasionxxx/ans/blob/main/85.jpg)

---

Соберем новую сборку и убедимся в наличии .jar

![image alt](https://github.com/vasionxxx/ans/blob/main/86.jpg)

---
