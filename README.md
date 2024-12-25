# ---===[ Fat Server ]===---
Игровой сервер Minecraft на версии Fabric 1.21.1

## Некоторые сведения
* ```Ванильный```, исключая генерацию
* Кастомная генерация с ```Big Globe``` и увеличенный размер мира - 2км
* Размер игрового мира: overworld 10000, nether 1250, the_end 10000
* Тепепортация на другой конец мира при достижении барьера
* Используется ```Alternate Current``` редстоун

## Моды на стороне сервера
| Название              | Версия  | Для чего                                             |
| :-------------------- | :-----: | :--------------------------------------------------- |
| Alternate Current     | 1.9.0   | Оптимизация редстоуна                                |
| Better Fabric Console | 1.2.0   | Улучшение вида консоли                               |
| Big Globe             | 4.8.4   | Новая генерация. Используется ```bigglobe:islands``` |
| C2ME                  | 0.3.0   | Оптимизация генерации                                |
| Chunky                | 1.4.16  | Прегенерация областей                                |
| Chunky Border         | 1.2.18  | Кастомные мировые барьеры                            |
| Collective            | 7.87    | Библиотека, используется ```World Borders```         |
| Easy Auth             | 3.0.25  | Авторизация на сервере                               |
| Fabric API            | 0.110.0 | API для fabric-модов                                 |
| FerritCore            | 7.0.2   | Оптимизация использования памяти                     |
| Graves                | 3.4.4   | Могилки для сохранения вещей при смерти              |
| Jade                  | 15.8.3  | Серверная сторона для клиентсткого мода Jade         |
| Krypton               | 0.2.8   | Оптимизация сети                                     |
| Lithium               | 0.13.1  | Оптимизация тикрейта                                 |
| ModernFix             | 5.19.6  | Общая оптимизация                                    |
| ScalableLux           | 0.1.0   | Оптимизация освещения                                |
| Server Core           | 1.5.5   | Оптимизация серверного ядра                          |
| World Border          | 4.7     | Кастомные мировые барьеры                            |

## Обязательные моды на стороне клиента

| Название              | Версия  |
| :-------------------- | :-----: |
| Big Globe             | 4.8.4   |
| Fabric API            | 0.110.0 |

## Предлагаемые моды на стороне клиента

### QoL
| Название              | Версия  | Для чего                                             |
| :-------------------- | :-----: | :--------------------------------------------------- |
| Apple Skin            | 3.0.6   | Улушчение пищевого HUD                               |
| Bobby                 | 5.2.4   | Увеличение дальности прорисовки на клиенте           |
| Chunky Border         | 1.2.18  | Отображение кастомных барьеров                       |
| Jade                  | 15.8.3  | Отображение информации о сущностях и блоках          |
| Lamb Dynamic Lights   | 3.1.4   | Свечение предметов в руках без шейдеров              |
| Roughly Enough Items  | 16.0.7  | Просмотр предметов и рецептов                        |
| Shulkerbox Tooltip    | 5.1.2   | Просмотр содежимого шалкеров                         |

### Красота
| Название                 | Версия  | Для чего                                             |
| :----------------------- | :-----: | :--------------------------------------------------- |
| Better Ping Display      | 1.1.1   | Улучшение ping-панели                                |
| Entity Model Features    | 2.4.1   | Поддержка ```Optifine```'овских особенностей моделей |
| Entity Texture Features  | 2.4.1   | Поддержка ```Optifine```'овских вариаций текстур     |
| Falling Leaves           | 1.16.4  | Падающие листья у деревьев                           |
| Iris                     | 1.8.1   | Шейдеры с ```Sodium```                               |
| Not Enough Animations    | 1.8.2   | Улучшенные анимации взаимодействий персонажа         |
| Particular               | 1.1.1   | Прикольные эмбиентные эффекты                        |
| Sound Physics Remastered | 1.4.8   | Улучшение звукового эмбиента                         |
| Subtle Effects           | 1.7.0   | Улучшение детализации посредствам звуков и частиц    |
| Visuality                | 0.7.7   | Новые прикольные частички                            |

### Оптимизация
| Название              | Версия  | Для чего                                             |
| :-------------------- | :-----: | :--------------------------------------------------- |
| Entity Culling        | 1.7.2   | Оптимизация отрисовки сущностей                      |
| Ferrite Core          | 7.0.2   | Оптимизация использования памяти                     |
| Immediately Fast      | 1.3.3   | Ускорение отрисовки                                  |
| Krypton               | 0.2.8   | Оптимизация сети                                     |
| Lithium               | 0.13.1  | Оптимизация тикрейта                                 |
| Modern Fix            | 5.19.6  | Общая оптимизация                                    |
| More Culling          | 1.0.3   | Улучшение производительности                         |
| Scalable Lux          | 0.1.0   | Оптимизация освещения                                |
| Sodium                | 0.6.5   | Оптимизация отрисовки чанков                         |

### Прочее
| Название              | Версия  | Для чего                                             |
| :-------------------- | :-----: | :--------------------------------------------------- |
| Big Globe             | 4.8.4   | Новая генерация                                      |
| Chunky                | 1.4.16  | Для ```Chunky Borders```                             |
| Mod Menu              | 11.0.3  | Панель управления модами                             |

### Библиотеки
| Название               | Версия  | Зависят                                              |
| :--------------------- | :-----: | :--------------------------------------------------- |
| Architectury           | 13.0.8  | Roughly Enough Items                                 |
| Fabric API             | 0.110.0 | Впринципе все                                        |
| Fabric Language Kotlin | 1.13.0  | Fzzy Config                                          |
| Fzzy Config            | 0.5.9   | Subtle Effects                                       |
| Owo Lib                | 0.12.15 | Particular                                           |
| Satin                  | 2.0.0   | Big Globe (optional)                                 |

