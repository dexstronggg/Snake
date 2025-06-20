# Snake Game (WPF, C#)

Этот проект представляет собой классическую аркадную игру **«Змейка»**, реализованную на языке C# с использованием технологии **WPF (Windows Presentation Foundation)**. Игра была разработана как выпускная квалификационная работа студента-программиста.

## 🎮 Описание игры

Игрок управляет змейкой, которая перемещается по полю, собирает еду и увеличивается в длину. Цель — набрать как можно больше очков, избегая столкновений со стенами и собственным телом.

## 🧩 Основные функции

* Движение змейки с помощью клавиш со стрелками (↑, ↓, ←, →)
* Генерация еды в случайной позиции
* Увеличение длины змейки при сборе еды
* Проверка столкновений (с границами и телом змейки)
* Счётчик очков
* Перезапуск игры после окончания

## 🖼 Интерфейс

Приложение имеет простое и понятное графическое окно:

* Игровое поле из квадратных ячеек
* Отображение текущего счёта
* Возможность начать новую игру после поражения

## 🚀 Как запустить

1. Убедитесь, что у вас установлен **.NET Framework** или **.NET 6/7+** (в зависимости от версии проекта).
2. Откройте решение в **Visual Studio**.
3. Соберите проект (`Ctrl + Shift + B`).
4. Запустите (`F5`) или используйте исполняемый файл из папки `bin/Debug`.

## 📂 Структура проекта

* `MainWindow.xaml` — основное окно с игровым интерфейсом.
* `MainWindow.xaml.cs` — обработка логики игры.
* `Snake.cs` — логика движения змейки.
* `Food.cs` — генерация еды.
* `GameEngine.cs` — основной цикл игры, таймер, столкновения и счёт.

## 📋 Зависимости

* .NET (WPF)
* System.Windows.Threading (для игрового таймера)

## 🧪 Тестирование

Проведено ручное тестирование на различных сценариях:

* Сбор еды
* Столкновение со стенами
* Столкновение с телом змейки
* Устойчивость при быстрой смене направления

## 🧑‍💻 Автор

Юрьев Илья — студент группы ПИЖ-б-о-22-1.

##
