## Извеждане на текст по шаблон (placeholder)

**Placeholder** представлява израз, който ще бъде заменен с конкретна стойност при отпечатване. Методите **`Console.Write(…)`** / **`WriteLine(…)`** поддържат печатане на текст по шаблон, като първият аргумент, който трябва да подадем, е форматиращият низ, следван от броя аргументи, равен на броя на плейсхолдърите.

```csharp
Console.WriteLine("You are {0} {1}, a {2}-years old person from {3}.",
  firstName, lastName, age, town);
```