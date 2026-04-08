# Calculator

Реализуйте класс `Calculator` в файле `src/Calculator/Calculator.cs`.

## Требования

Класс `Calculator` должен содержать 4 метода:

| Метод | Сигнатура | Описание |
|---|---|---|
| `Add` | `double Add(double a, double b)` | Возвращает сумму `a + b` |
| `Subtract` | `double Subtract(double a, double b)` | Возвращает разность `a - b` |
| `Multiply` | `double Multiply(double a, double b)` | Возвращает произведение `a * b` |
| `Divide` | `double Divide(double a, double b)` | Возвращает частное `a / b`. При `b == 0` выбрасывает `DivideByZeroException` |

## Как работать

1. Откройте `src/Calculator/Calculator.cs`
2. Реализуйте все 4 метода
3. Для локальной проверки: `dotnet build src/Calculator/`
4. Отправьте ссылку на этот репозиторий через систему автопроверки

> **Примечание:** папка `tests/` отсутствует — скрытые тесты запускаются автоматически в CI.
> Не удаляйте и не переименовывайте файл `Calculator.slnx`.

