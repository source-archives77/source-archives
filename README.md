# ChessNavio

Исходный код расширения ChessNavio по лицензии GPL-3.0.

ChessNavio показывает шахматные подсказки прямо рядом с доской: основной ход,
короткую идею и варианты под выбранный уровень. Завершённую партию можно
разобрать по PGN или FEN без установки — на
[chessnavio.ru/analyze](https://chessnavio.ru/analyze).

Анализ выполняется на вашем компьютере. Во время партии позиции и подсказки не
отправляются на сервер.

Сайт: [chessnavio.ru](https://chessnavio.ru)

## Установка

ChessNavio устанавливается из
[Chrome Web Store](https://chromewebstore.google.com/detail/chessnavio/plegfgbhkjlghbpfkbihkennpjecaigd);
браузер обновляет его сам. Пошагово:
[chessnavio.ru/install](https://chessnavio.ru/install?utm_source=github&utm_medium=referral&utm_content=readme).

Если ChessNavio у вас установлен вручную из ZIP, поставьте версию из Chrome Web
Store рядом, войдите и проверьте её; старую копию удаляйте после проверки.

## Что здесь лежит

- Начиная с 2.0.0 выпуски содержат только исходный код: архив
  `ChessNavio-extension-source-*.tar.gz` (расширение, пакеты, из которых оно
  собирается, скрипты сборки), исходники встроенных Stockfish.js и Maia,
  список лицензий, SBOM и `SHA256SUMS.txt`. Архивов для установки в них нет.
- Выпуски до 1.3.3 включительно оставлены без изменений: на них ссылаются
  уже установленные вручную копии.

Встроенные Stockfish.js и Maia распространяются по GPLv3, поэтому исходный код
каждой опубликованной версии расширения выкладывается здесь. Стабильные
выпуски **неизменяемы**: GitHub не позволяет заменить их файлы или перенести
тег.

Проверка неизменяемости выпуска (GitHub CLI):

```bash
gh release verify v2.0.0 --repo 12hsrate-hub/chessnavio-releases
```

Перед использованием подсказок проверьте правила выбранной шахматной площадки.

Поддержка: [support@chessnavio.ru](mailto:support@chessnavio.ru)
