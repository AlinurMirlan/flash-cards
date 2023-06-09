# Flash cards
Веб-сайт, упрощающий процесс повторения информации что вы желаете запомнить (в моём случае это были иностранные слова). Все записи организованы в тематические колоды, что помогает навести порядок.
### Мотивация
Мне, как человеку, заинтересованному иностранными языками, важно не забывать пополнять словарный запас. Вести словарик можно разными способами, будь то запись выражений в специально определенной для словаря группе в мессенджере (как когда-то делал я), либо в старой доброй тетради; но какой бы способ это ни был, всё сводится к повтору записей для дальнейшего их запоминания; а делать это вручную представляет большие трудности.
Я решил взяться за автоматизацию процесса слежения за повторениями записей и создать сайт для их хранения и запоминания. 
## Руководство пользователя
Приветствую вас, Пользователь!
* При первом доступе на веб-сайт, вас попросят зарегистрироваться в целях идентификации, после чего вы получите доступ к веб-сайту.
* Прежде чем добавлять карточки, вам нужно создать колоду для её хранения. Сделано это с целью разделения разных по тематике карточек, скажем, есть у вас одна колода для хранения иностранных слов, а вторая для тем по подготовке к экзамену.
* Все карточки, которые необходимо повторить, отображаются на странице Rehearse. Вы всегда можете изменить, либо удалить карту, при помощи кнопки дополнительного функционала (графически выглядит так: \*\*\*) справа сверху карточек.
* Если же вы хотите просмотреть все существующие карточки колоды, перейдите на страницу Browse, где вы также можете манипулировать картами с помощью кнопки (\*\*\*) 
* В целях удобства, на страницах Decks и Browse есть поля для поиска желаемой вами информации. В странице Decks вы можете запросить поиск колоды с определенным именем, а в Browse карточку, содержащую заданный текст.
* Для смены пароля или доступа к почте перейдите на страницу Profile -> Settings. И наконец, для выхода из сессии, пройдите на Profile -> Logout. 

### Использованные технологии
ASP.NET Core Razor Pages, EF Core
