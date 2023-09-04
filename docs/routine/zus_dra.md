title: Подача декларації ZUS 

# Коли подавати

До 20 числа кожного місяця, після [оплати внесків до ZUS](/routine/zus)

## Збереження DRA файлу

1. `infakt` -> `Księgowość` ->`Przegląd` -> `Składki ZUS` -> `Opłać teraz` -> `Przejdź do składki`
<a>![alt taxes tab](../img/zus_dra/select_skladka.jpg) </a>
2. Тиснемо `Pobierz ZUS DRA` щоб стянути DRA (я зберігаю в `FOP Pol\ZUS checks`)
<a>![alt taxes tab](../img/zus_dra/download_dra_from_infakt.jpg) </a>

## Заливання DRA файлу в ZUS
1. Логінемося в [ZUS](https://www.zus.pl/portal/logowanie.npi) через довірчий профіль (profil zaufany). Воно інколи тупить, можна через щось подібне до банкІд
<a>![alt taxes tab](../img/zus_dra/zus_log_in.jpg) </a>
2. Заходимо в закладку [ePlatnik](https://www.zus.pl/portal/eplMain.npi) -> `Dokumenty` -> `Import KEDU`
<a>![alt import kedu](../img/zus_dra/zus_select_import_kedu.jpg) </a>
3. Проходимо `Dalej` до кроку 2 (`Wybór pliku do importu i generacja dokumentów synchronizujących)
4. Тиснемо `Wybierz plik...` і вибираємо *.dra файл
 <a>![alt select plik](../img/zus_dra/select_plik.jpg) </a>
5. Проходимо `Dalej` до кроку 3 (`Utworzenie i walidacja dokumentów`)  
6. Вибераємо `ZUS DRA`
7. Тиснемо `Edytuj`
<a>![alt edit dra](../img/zus_dra/edit_dra.jpg) </a>
8. Валідємо, натиснувши `Sprawdź` і далі `Zamknij` (сподіватимемось, що не буде помилки)
9. Натиснути Zakończ і перейти в до вкладки `Dokumenty robocze`
10. Якщо статус не OK (чомусь) - `Weryfikuj`
11. Якщо статус OK - `Zatwierdź`
<a>![alt work docs](../img/zus_dra/zus_work_docs.jpg) </a>
12. Перейти в до вкладки `Dokumenty zatwierdzone`
13. Тиснемо `Wyślij`
<a>![alt confirmed docs](../img/zus_dra/zus_confirmed_docs.jpg) </a>
14. Підписуємо ePUAP (довірчий профіль). Чогось зараз не спрацював, спробую вислати завтра
