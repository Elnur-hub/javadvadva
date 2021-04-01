# Отчет о тестировании бонусной системы для клиентов

## Краткое описание

1.04.2021 было проведено функциональное тестирование бонусной системы для клиентов

На тестирование затрачено: 30 минут

В результате тестирования выявлены следующие дефекты:

* При сложении регулярного и специального бонуса итоговая сумма отображается неверно [скриншот] (https://sun9-12.userapi.com/impf/Hb2i2jLG_CcICFG-IaYJIX60tcfrTNwKd7yKsQ/1p8DVCWrXMQ.jpg?size=1919x1038&quality=96&sign=66c2ff667373a5bd48ccb955bf062411&type=album)

## Описание процесса тестирования 

В  процессе тестирования использовались следующие артефакты:

* Тестовый сценарий:

1. Использовать представленный ниже код 

public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}

2. Открыть IntelliJ IDEA, создать файл Main.Java и вставить в него код

3. Воспроизвести код нажатием на кнопку Run или CTRL+SHIFT+F10

4. Зафиксировать результаты запуска

В качестве тестовых данных использовался предоставленный код:

* public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}

Тестирование производилось в следующем окружении:
* Windows 10 Home 64-bit
* Java 11.0.10+9
* IntelliJ IDEA Community Edition 2020.3.3