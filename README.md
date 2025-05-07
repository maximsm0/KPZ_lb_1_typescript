# Лабораторна робота №1: Ознайомлення з TypeScript

## Мета

Ознайомитися з основами мови TypeScript: типізацією, інтерфейсами, класами, композитними типами та дженериками.

### 1. Типізація змінних
- Оголошено змінні типів: `string`, `number`, `boolean`, `array`, `object`.
- Реалізовано функцію, яка приймає об'єкт з `name` та `age` і повертає форматований рядок.
![image](https://github.com/user-attachments/assets/394083d8-97e8-46c4-8a4d-4b7462a68e98)

### 2. Інтерфейси
- Оголошено інтерфейс `Person` з опціональним полем `address`.
- Реалізовано функцію `printPerson()`, яка виводить дані користувача.
![image](https://github.com/user-attachments/assets/055f8a4c-7db0-429b-9927-f39a03a7814e)

### 3. Композитні типи
- Оголошено тип `Status = 'success' | 'error' | 'loading'`.
- Реалізовано функцію `showStatusMessage()`, яка реагує на значення статусу.
![image](https://github.com/user-attachments/assets/26759743-938e-4974-8928-a2242e7612c0)

### 4. Дженерики
- Реалізовано функцію `identity<T>(value: T): T`.
- Продемонстровано її використання з типами `number`, `string`, `boolean`.
![image](https://github.com/user-attachments/assets/30f3c227-7e20-4731-8fdd-5bbb3ddbfa47)

### 5. Класи
- Створено клас `Car` з полями `model`, `year`.
- Реалізовано метод `getCarInfo()`, який повертає опис авто.
![image](https://github.com/user-attachments/assets/8cbf362d-0192-4af6-aebd-c6ba21cea4c1)
