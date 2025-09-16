# CorelDraw-Curve-Length-Tool

[![CorelDRAW](https://img.shields.io/badge/For-CorelDRAW-blue.svg)](https://www.coreldraw.com)
[![VBA](https://img.shields.io/badge/Made%20with-VBA-important)](https://docs.microsoft.com/en-us/office/vba/api/overview/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**English** | [Русский](#русский)

A VBA macro for CorelDRAW that calculates the total length of all selected curves and places the dimension text next to them. The length is rounded to the nearest 25 units for a cleaner look.

---

## Features
- Calculates the length of single or multiple selected curves.
- Automatically creates artistic text with the dimension.
- Places the text above the center of the curve.
- Rounds the result for better readability.

## Installation
1.  Download the `.gsl` file from the [Releases](../../releases) section.
2.  In CorelDRAW, open the Macro Manager (`Tools > Macros > Macro Manager`).
3.  In the Macro Manager docker, click on the "Import" button (blue down arrow).
4.  Select the downloaded `.gsl` file.
5.  The macro will appear under "Project Macros". You can now run it from the Macro Manager or assign it to a toolbar shortcut.

## Usage
1.  Select one or more curve shapes in your CorelDRAW document.
2.  Run the macro `GetCurveLength`.
3.  The macro will calculate the total length, round it, and place text objects above each selected curve.

## Русский

VBA-макрос для CorelDRAW, который вычисляет общую длину всех выбранных кривых и размещает размерный текст рядом с ними. Длина округляется до ближайших 25 единиц для более аккуратного вида.

## Установка
1.  Скачайте файл `.gsl` в разделе [Releases](../../releases).
2.  В CorelDRAW откройте Менеджер макросов (`Сервис > Макросы > Менеджер макросов`).
3.  В докере Менеджера макросов нажмите кнопку "Импорт" (синяя стрелка вниз).
4.  Выберите скачанный файл `.gsl`.
5.  Макрос появится в разделе "Макросы проектов". Теперь его можно запустить из Менеджера макросов или назначить кнопку на панели инструментов.

## Использование
1.  Выделите одну или несколько кривых в вашем документе CorelDRAW.
2.  Запустите макрос `GetCurveLength`.
3.  Макрос рассчитает общую длину, округлит её и разместит текстовые объекты над каждой выбранной кривой.
