# Савич Артём Александрович
![Image alt](https://github.com/SavichArtem/WebProgramming/blob/gh-pages/Web/assets/avatar.png)
## Обо мне:
Я начинающий программист и моя цель — стать квалифицированным разработчиком программного обеспечения. <br>
Мои приоритеты на данный момент — это углубление знаний в языках программирования. Сейчас я активно изучаю язык программирования С# и основы веб-разработки. <br>
Я считаю, что мои сильные стороны — это умение работать в команде
и способность быстро усваивать новую информацию. Стремлюсь постоянно развиваться, чтобы стать ценным специалистом в своей области. <br>
Я открыт к новым знаниям и готов работать над сложными задачами, чтобы улучшать свои навыки.
## Опыт работы:
Сверстал CV, в котором отобразил информацию о себе, свои профессиональные достижения и навыки. <br>
В ходе выполнения проекта улучшил свои навыки вёрстки, а также изучил новые теги, которые применил в CV. <br>
### Мои навыки:
1. Владею языком программирования **C#**
2. Умею работать с **SQL**
3. Знаю основы работы с **Git**
4. Умею работать в команде
### Уровень английского - B1
### Примеры кода:
```
static void ShowStudent(Student[] students)
{
 for (int i = 0; i < students.Length; i++)
 {
    Console.WriteLine($"Студент [{i + 1}]");
    Console.WriteLine($"Id студента: {students[i].Id}");
    Console.WriteLine($"ФИО: {students[i].Name}");
    Console.WriteLine($"Группа: { students[i].Group}\n");
 }
}
```

```
static Status[] ReadStatusesFromFile(StreamReader statusPath)
{
 string[] lines;
 using (StreamReader srStat = new("..\\..\\..\\Status.txt"))
 {
   lines = srStat.ReadToEnd().Split('\n');
 }
 int length = lines.Length / 3;
 Status[] stat = new Status[length];
 for (int i = 0; i < length; i++)
 {
   stat[i] = ReadStatusFromFile(statusPath);
 }
 return stat;
}
```
### Связаться со мной:
+ [Gmail](savichaa.pir231@gmail.com)
+ [VK](https://vk.com/id252364585)
+ [Git](https://github.com/SavichArtem)
