1. Підтягнути файл використовуючи ClassLoader
2. Використати inputStream.readAllBytes()
3. Не перезаписувати зміну content, зробити окремі змінні fileContent та cleanedFileContent
4. Замінити регулярний вираз на [^\w\s] - not word or whitespace
5. Замінити регулярний вираз спліта на \s+
6. Прибрати зайве сортування `Arrays.sort(words);`
7. Замінити створення `String distinctString = " "` і спліт за пробілом на `List<String> distinctWords = new ArrayList<>();`
8. Коли визначаємо унікальні слова передбачити що рядок може бути пустий
9. Cтворити клас Word який міститиме текст слова та його кількість
10. Замінти звичайні for цикли на foreach цикли
11. Так як тепер працюємо з List та об'єктами, можна використати звичайний `sort()` з компаратором без зайвої конвертації String у Integer
