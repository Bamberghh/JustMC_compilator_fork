## Игровые значения

Пример использования:
```ts
var a = value::location
var b = value::health<default_entity>
```

### Доступные селекторы

**Важно:** эти селекторы доступны только для игровых значений.Действия имеют свои собственные селекторы, которые вы должны смотреть на их страницах.

| **Имя**            | **Описание**          |
| ------------------ | --------------------- |
| `<current>`        | Текущая цель          |
| `<default>`        | По умолчанию          |
| `<default_entity>` | Существо по умолчанию |
| `<killer_entity>`  | Убийца                |
| `<damager_entity>` | Атакующий             |
| `<victim_entity>`  | Жертва                |
| `<shooter_entity>` | Стрелок               |
| `<projectile>`     | Снаряд                |
| `<last_entity>`    | Последняя сущность    |### Значения

| **Id**                               | **Название**                                                                                                                                                                                                        |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `value::current_health`              | Текущее здоровье                                                                                                                                                                                                    |
| `value::max_health`                  | Максимальное здоровье                                                                                                                                                                                               |
| `value::absorption_health`           | Дополнительное здоровье                                                                                                                                                                                             |
| `value::food_level`                  | Уровень голода                                                                                                                                                                                                      |
| `value::food_saturation`             | Уровень насыщения                                                                                                                                                                                                   |
| `value::food_exhaustion`             | Уровень истощения                                                                                                                                                                                                   |
| `value::attack_damage`               | Урон от атаки                                                                                                                                                                                                       |
| `value::attack_speed`                | Скорость атаки                                                                                                                                                                                                      |
| `value::armor_points`                | Очки защиты                                                                                                                                                                                                         |
| `value::armor_toughness`             | Твёрдость брони                                                                                                                                                                                                     |
| `value::invulnerability_ticks`       | Время бессмертия                                                                                                                                                                                                    |
| `value::experience_level`            | Уровень опыта                                                                                                                                                                                                       |
| `value::experience_progress`         | Прогресс опыта                                                                                                                                                                                                      |
| `value::fire_ticks`                  | Время горения                                                                                                                                                                                                       |
| `value::freeze_ticks`                | Время заморозки                                                                                                                                                                                                     |
| `value::remaining_air`               | Оставшийся воздух                                                                                                                                                                                                   |
| `value::fall_distance`               | Дистанция падения                                                                                                                                                                                                   |
| `value::held_slot`                   | Выбранный слот в хот-баре                                                                                                                                                                                           |
| `value::walking_speed`               | Скорость ходьбы                                                                                                                                                                                                     |
| `value::flying_speed`                | Скорость полёта                                                                                                                                                                                                     |
| `value::ping`                        | Пинг игрока                                                                                                                                                                                                         |
| `value::protocol_version`            | Версия протокола клиента                                                                                                                                                                                            |
| `value::item_usage_progress`         | Прогресс использования предмета                                                                                                                                                                                     |
| `value::entity_ticks_lived`          | Время жизни цели                                                                                                                                                                                                    |
| `value::arrows_in_body`              | Количество стрел в теле                                                                                                                                                                                             |
| `value::age`                         | Возраст цели                                                                                                                                                                                                        |
| `value::steer_forward`               | Прямолинейное движение транспорта                                                                                                                                                                                   |
| `value::steer_sideways`              | Движение транспорта в стороны                                                                                                                                                                                       |
| `value::merchant_recipe_count`       | Количество торгов Жителя                                                                                                                                                                                            |
| `value::open_inventory_size`         | Размер открытого инвентаря<br/>**Работает с:** Игроками                                                                                                                                                             |
| `value::entity_width_x`              | Ширина хитбокса                                                                                                                                                                                                     |
| `value::entity_height`               | Высота хитбокса                                                                                                                                                                                                     |
| `value::entity_width_z`              | Длина хитбокса                                                                                                                                                                                                      |
| `value::location`                    | Местоположение                                                                                                                                                                                                      |
| `value::target_block_location`       | Местоположение целевого блока                                                                                                                                                                                       |
| `value::target_fluid_location`       | Местоположение целевой жидкости                                                                                                                                                                                     |
| `value::target_block_face`           | Сторона целевого блока                                                                                                                                                                                              |
| `value::eye_location`                | Местоположение глаз                                                                                                                                                                                                 |
| `value::x_coordinate`                | Координата X                                                                                                                                                                                                        |
| `value::y_coordinate`                | Координата Y                                                                                                                                                                                                        |
| `value::z_coordinate`                | Координата Z                                                                                                                                                                                                        |
| `value::pitch`                       | Вертикальный поворот                                                                                                                                                                                                |
| `value::yaw`                         | Горизонтальный поворот                                                                                                                                                                                              |
| `value::direction_of_view`           | Направление взгляда                                                                                                                                                                                                 |
| `value::cardinal_direction`          | Кардинальное направление                                                                                                                                                                                            |
| `value::hitbox_midpoint_location`    | Центр хитбокса                                                                                                                                                                                                      |
| `value::spawn_location`              | Местоположение спавна мира                                                                                                                                                                                          |
| `value::origin`                      | Местоположение первого появления                                                                                                                                                                                    |
| `value::velocity`                    | Вектор скорости                                                                                                                                                                                                     |
| `value::body_yaw`                    | Поворот тела                                                                                                                                                                                                        |
| `value::block_beneath`               | Местоположение блока под целью                                                                                                                                                                                      |
| `value::blocks_beneath`              | Блоки под целью                                                                                                                                                                                                     |
| `value::main_hand_item`              | Предмет в ведущей руке                                                                                                                                                                                              |
| `value::off_hand_item`               | Предмет во второй руке                                                                                                                                                                                              |
| `value::armor_items`                 | Предметы брони                                                                                                                                                                                                      |
| `value::hotbar_items`                | Предметы в хот-баре                                                                                                                                                                                                 |
| `value::inventory_items`             | Предметы в инвентаре                                                                                                                                                                                                |
| `value::custom_inventory_items`      | Список предметов в открытом инвентаре                                                                                                                                                                               |
| `value::cursor_item`                 | Предмет на курсоре                                                                                                                                                                                                  |
| `value::saddle_item`                 | Предмет на седле<br/>**Работает с:** Свиньями,Лошадьми,Ламами                                                                                                                                                       |
| `value::entity_item`                 | Предмет сущности<br/>**Работает с:** Предметами,Выброшенными зельями,Фейерверками,Стрелами,Падающими блоками,Другими снарядами                                                                                      |
| `value::name`                        | Имя                                                                                                                                                                                                                 |
| `value::uuid`                        | UUID                                                                                                                                                                                                                |
| `value::display_name`                | Отображаемое имя                                                                                                                                                                                                    |
| `value::entity_type`                 | Тип сущности                                                                                                                                                                                                        |
| `value::client_brand_name`           | Название клиента игрока<br/>**Работает с:** Игроками                                                                                                                                                                |
| `value::user_locale`                 | Язык клиента игрока<br/>**Работает с:** Игроками                                                                                                                                                                    |
| `value::open_inventory_title`        | Заголовок открытого инвентаря<br/>**Работает с:** Игроками                                                                                                                                                          |
| `value::open_inventory_type`         | Тип открытого инвентаря<br/>**Работает с:** Игроками                                                                                                                                                                |
| `value::gamemode`                    | Режим игры<br/>**Работает с:** Игроками                                                                                                                                                                             |
| `value::last_damage_cause`           | Последняя причина урона                                                                                                                                                                                             |
| `value::potion_effects`              | Эффекты зелий                                                                                                                                                                                                       |
| `value::vehicle`                     | Транспорт                                                                                                                                                                                                           |
| `value::passengers`                  | Пассажиры                                                                                                                                                                                                           |
| `value::lead_holder`                 | Поводырь                                                                                                                                                                                                            |
| `value::attached_leads`              | Привязанные сущности                                                                                                                                                                                                |
| `value::targeted_entity`             | Цель для атаки                                                                                                                                                                                                      |
| `value::spawn_reason`                | Причина спавна                                                                                                                                                                                                      |
| `value::main_hand`                   | Ведущая рука<br/>**Работает с:** Игроком                                                                                                                                                                            |
| `value::event_block_location`        | Местоположение блока события<br/>**Работает с:** Событиями взаимодействия,Событиями установки или поломки блоков,Событием попадания снаряда,Событиями блоков в мире                                                 |
| `value::event_block_face`            | Сторона блока события<br/>**Работает с:** Событиями взаимодействия,Событиями установки или поломки блоков,Событием попадания снаряда,Событиями поршней                                                              |
| `value::event_blocks_involved`       | Задействованные блоки события<br/>**Работает с:** Событиями взрывов,Событиями поршней                                                                                                                               |
| `value::event_interaction`           | Тип взаимодействия события<br/>**Работает с:** Событием Правый клик,Событием Левый клик,Событием взаимодействия                                                                                                     |
| `value::event_new_location`          | Новая локация игрока<br/>**Работает с:** Событием "Игрок передвигается",Событием "Игрок прыгает",Событием "Игрок телепортировался",Событием "Игроку не удалось передвинуться",Событием "Падающий блок приземляется" |
| `value::event_damage`                | Нанесённый урон<br/>**Работает с:** Событиями получения урона игроком,Событиями получения урона сущностью,Событиями получения урона транспортом                                                                     |
| `value::event_damage_cause`          | Причина полученного урона<br/>**Работает с:** Событием Игрок получает урон,Событием Сущность получает урон,Событием Транспорт получает урон                                                                         |
| `value::event_chat_message`          | Сообщение чата<br/>**Работает с:** Событием игрока Сообщение                                                                                                                                                        |
| `value::event_message`               | Сообщение события<br/>**Работает с:** Событием игрок присоединился,Событием игрок вышел,Событием игрок умер                                                                                                         |
| `value::event_heal_amount`           | Количество восстановленного здоровья<br/>**Работает с:** Событием Игрок восстанавливает здоровье,Событием Сущность восстанавливает здоровье                                                                         |
| `value::event_heal_cause`            | Причина исцеления<br/>**Работает с:** Событием Игрок восстанавливает здоровье,Событием Сущность восстанавливает здоровье                                                                                            |
| `value::event_new_potion_effect`     | Новый эффект<br/>**Работает с:** Событием "Игрок получает эффект от взрывного зелья"                                                                                                                                |
| `value::event_power`                 | Процент силы выполнения<br/>**Работает с:** Событием игрока Стреляет,Событием прыжка на лошади                                                                                                                      |
| `value::event_item`                  | Предмет события<br/>**Работает с:** Событиями с предметами,Событием рыбалки,Событием редактирования книги,Событием игрока Стреляет                                                                                  |
| `value::event_items`                 | Предметы события<br/>**Работает с:** Обмен с пиглином                                                                                                                                                               |
| `value::event_equipment_slot`        | Тип задействованного слота<br/>**Работает с:** Событием Правый клик,Событием Левый клик,Событием взаимодействия,Событием взмаха руки                                                                                |
| `value::event_slot`                  | Слот события<br/>**Работает с:** Событием смены слота хот-бара,Событием клика в своём инвентаре,Событием клика в открытом инвентаре,Событием крафта,Событием нахождения предмета в инвентаре                        |
| `value::event_hotbar_slot`           | Слот хот-бара в событии<br/>**Работает с:** Событием смены слота,Событием клика в своём инвентаре,Событием клика в открытом инвентаре,Событием нахождения предмета в инвентаре                                      |
| `value::event_added_items`           | Распределённые предметы<br/>**Работает с:** Событием перетягивания предметов                                                                                                                                        |
| `value::event_slot_type`             | Тип слота при клике<br/>**Работает с:** Событием клика в своём инвентаре,Событием клика в открытом инвентаре                                                                                                        |
| `value::event_close_inventory_cause` | Причина закрытия инвентаря<br/>**Работает с:** Событием закрытия инвентаря                                                                                                                                          |
| `value::event_inventory_click_type`  | Тип клика по инвентарю<br/>**Работает с:** Событием клика в своём инвентаре,Событием клика в открытом инвентаре                                                                                                     |
| `value::event_inventory_action`      | Действие в инвентаре при клике<br/>**Работает с:** Событием клика в своём инвентаре,Событием клика в открытом инвентаре                                                                                             |
| `value::event_drag_type`             | Тип перетягивания по инвентарю<br/>**Работает с:** Событием перетягивания предметов                                                                                                                                 |
| `value::event_slots_involved`        | Задействованные слоты<br/>**Работает с:** Событием перетягивания предметов                                                                                                                                          |
| `value::event_fish_state`            | Причина события рыбалки<br/>**Работает с:** Событием рыбалки                                                                                                                                                        |
| `value::event_tree_type`             | Тип дерева<br/>**Работает с:** Событием игрока "Выращивает дерево",Событием мира "Дерево вырастает"                                                                                                                 |
| `value::event_experience`            | Количество опыта события<br/>**Работает с:** Событием рыбалки,Событием получения опыта,Событиями смерти                                                                                                             |
| `value::event_hanging_break_cause`   | Причина удаление висящей сущности<br/>**Работает с:** Событием ломания висящей сущности                                                                                                                             |
| `value::event_time_skip_reason`      | Причина пропуска времени<br/>**Работает с:** Событием пропуска времени                                                                                                                                              |
| `value::event_time_skip_amount`      | Количество тиков пропуска времени<br/>**Работает с:** Событием пропуска времени                                                                                                                                     |
| `value::event_food_level`            | Восполненный голод события<br/>**Работает с:** Событием изменения уровня голода                                                                                                                                     |
| `value::event_projectile_item`       | Предмет снаряда события<br/>**Работает с:** Событием игрока Стреляет                                                                                                                                                |
| `value::event_teleport_cause`        | Причина телепортации<br/>**Работает с:** Событием телепортации игрока,Событием побега Эндермена                                                                                                                     |
| `value::event_ticks_held_for`        | Количество тиков использования предмета<br/>**Работает с:** Событием игрока "Перестает использовать предмет"                                                                                                        |
| `value::event_query_info`            | Отладочная информация<br/>**Работает с:** Событием "Игрок получает информацию о блоке",Событием "Игрок получает информацию о сущности"                                                                              |
| `value::event_fail_move_reason`      | Причина неудачного перемещения<br/>**Работает с:** Событием "Игроку не удалось передвинуться"                                                                                                                       |
| `value::event_transformed_entities`  | Замененные сущности события<br/>**Работает с:** Событием замены сущности                                                                                                                                            |
| `value::event_transform_reason`      | Причина замены сущности<br/>**Работает с:** Событием замены сущности                                                                                                                                                |
| `value::event_replaced_block`        | Заменённый блок<br/>**Работает с:** Событием "Игрок ставит блок"                                                                                                                                                    |
| `value::player_count`                | Количество игроков в мире                                                                                                                                                                                           |
| `value::cpu_usage`                   | Процент использования процессора                                                                                                                                                                                    |
| `value::server_tps`                  | TPS сервера                                                                                                                                                                                                         |
| `value::timestamp`                   | UNIX-время                                                                                                                                                                                                          |
| `value::server_current_tick`         | Текущее время сервера                                                                                                                                                                                               |
| `value::selection_size`              | Количество выбранных целей                                                                                                                                                                                          |
| `value::selection_target_names`      | Имена выбранных целей                                                                                                                                                                                               |
| `value::selection_target_uuids`      | UUID выбранных целей                                                                                                                                                                                                |
| `value::url_response`                | Ответ на веб-запрос<br/>**Работает с:** Событием "Ответ от сервера"                                                                                                                                                 |
| `value::url_response_code`           | Код ответа на веб-запрос<br/>**Работает с:** Событием "Ответ от сервера"                                                                                                                                            |
| `value::url`                         | Ссылка веб-запроса<br/>**Работает с:** Событием "Ответ от сервера"                                                                                                                                                  |
| `value::world_time`                  | Текущее время мира                                                                                                                                                                                                  |
| `value::world_weather`               | Текущая погода мира                                                                                                                                                                                                 |
| `value::server_stopped_time`         | Время остановки сервера                                                                                                                                                                                             |
| `value::action_count_per_tick`       | Количество действий за тик                                                                                                                                                                                          |
| `value::owner_uuid`                  | UUID владельца мира                                                                                                                                                                                                 |
| `value::world_size`                  | Размер мира                                                                                                                                                                                                         |
| `value::world_id`                    | ID мира                                                                                                                                                                                                             |