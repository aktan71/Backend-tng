# BACKEND
## Пособие по обучению
![Легенда](images/volga.jpg)
```java public class Main {
public static void main(String[] args) {
int[] numbers = {3, 5, 7, 2, 8, -1, 4, 10, 12};

        int min = numbers[0];
        int max = numbers[0];
        int sum = 0;

        // Ищем минимальное и максимальное значение в массиве, а также сумму всех чисел
        for (int number : numbers) {
            if (number < min) {
                min = number;
            }
            if (number > max) {
                max = number;
            }
            sum += number;
        }

        // Вычисляем среднее значение
        double average = (double) sum / numbers.length;

        // Выводим результаты
        System.out.println("Минимальное значение: " + min);
        System.out.println("Максимальное значение: " + max);
        System.out.println("Среднее значение: " + average);
    }
}
`