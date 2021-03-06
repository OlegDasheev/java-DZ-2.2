## Отчёт о тестировании приложения "Дополнительный бонус"

### Краткое описание

Проведено тестирование приложение "Дополнительный бонус". Был введен кусок кода в базовое приложение.
~~~javasscript
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
~~~

Проверена его работоспособность.

### Описание тестов
Тестирование методом SMOKE
TESTING.

### Результаты

Не успешный тест - 1

[При проверке нового кода для приложения "Дополнительный бонус" сумма итогового бонуса неправильный](https://github.com/OlegDasheev/java-DZ-2.2/issues)

### Общие рекомендации

Проводить тестировние в IntelliJ IDEA