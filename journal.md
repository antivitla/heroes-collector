Нужно иметь дело с однофамильцами. От этого два вопроса:

(1) как хранить однофамильцев или вообще героев
(2) как определять для каждого ресурса что речь о том же герое?
(3) как подставлять распознанного однофамильца - как дать выбор человеку кого подставлять?

В случае с zmil уникальность определяется через url фото. Это решается (2). Ну а хранить видимо как массив.

А кодировка группы? Там опять по имени... Всех по айди, которое динамическое есть одна из ссылок ресурсов. Через id/url любого из ресурсов

---

Как сохранять?

Имея героя, мы должны используя его ресурсные данные, начиная с zmil найти уже существующего героя.

Для телеграма использовать не имя канала как ресурс, а полный ключ — с префиксом `telegram.`, напр. `telegram.mod_russia`.