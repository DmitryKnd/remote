## Twitter Botstrap 

## Начало работы
**Твиттер борстреп** - твиттер [оф.сайт](https://netology.ru/)


Варианты установки:
* Правильно
* Неправильно


### Установка

1. Выполнить команду
1. Хорошо выполнить

## Использовать

```java
class Main {
  public static void main(String[] args) {
    java.util.Scanner myScanner = new java.util.Scanner(System.in);
    System.out.println("Введите первое число:");
    int value1 = myScanner.nextInt();
    System.out.println("Введите второе число:");
    int value2 = myScanner.nextInt();
    System.out.println("Введите третье число:");
    int value3 = myScanner.nextInt();
    int result = sumMethood(value1, value2, value3);
    System.out.println("Результат сложения:" + result);
  }
  
  static int sumMethood (int value1, int value2, int value3) {
    return  value1 + value2 + value3;
  }
 }
```

