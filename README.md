# «А помните    интернет»

<img src="remember.jpg" alt="Sad Cat" width="500" align="center" />

<br>
Белый список для Clash Verge; составляется, по большому счёту, для себя и исходя из стадии «шизофрении» моего провайдера

## Что включено в список:
*Примечание: конфиг рассчитан на использование «ультимативного конфига», в котором уже имеется определённый набор правил*
<details>
    <summary>Настольные клиенты</summary>

- Discord
- discord

*(оба варианта написания нужны для корректной работы апдейтера на Linux)*
</details>

<details>
    <summary>Прочие приложения</summary>

- KKManager.exe *(без прокси не может проверить наличие обновлений)*

</details>

<details>
    <summary>Заблокировано с ИХ стороны</summary>

- adobe.com
- broadcom.com
- deepl.com
- game8 *(.co и .jp)*
- grok.com, x.ai
- ko-fi.com
- ubisoft.com, ubi.com *(нужны для «халявы», недоступной в РФ)*
- wetransfer.com, we.tl
</details>

<details>
    <summary>Заблокировано с НАШЕЙ стороны</summary>

- donmai.us
- itch *(.io и .zone)*
- joyreactor.cc, reactor.cc
- knowyourmeme.com, kym-cdn.com
- pb.wtf ⚠️
- pixiv.net *(их медиа-сервер не блокируется)*
- play.google.com *(Play Маркет не открывается только с ПК, на телефонах он как работал, так и работает)*
- rutracker.org, rutracker.cc ⚠️
- ryuugames.com
- vndb.org

⚠️ – отсутствуют в перечне правил `torrent` в «ультимативном конфиге»
</details>

<details>
    <summary>Попали под горячую руку («ловушка 16 КБ»)</summary>

- adoptium.net
- b-cdn.net *(сервер обновлений, используемый Revo Uninstaller Pro)*
- bepis.moe
- betterrepack.com
- bookstackapp.com
- brew.sh
- catgirl.cloud
- cryptii.com, wierk.net
- cyberduck.io, duck.sh, mountainduck.io
- dawn.wine
- entergram.co.jp
- flathub.org
- gofile.io
- interactivemap.app
- mobian.org
- mycdn.ink *(медиа-сервер plati.market)*
- neverness.gg
- ntegame.com
- orangefox *(.tech и .download)*
- pawchive.st
- phpbb.com
- postmarketos.org
- protondb *(.com и head.protondb.pages.dev)*
- pushsquare.com
- steamgriddb.com
- userstorage.mega.co.nz *(mega.nz не блокируется)*
- wikia.nocookie.net *(static. и script.; fandom.com не блокируется)*
- xbox.com *(microsoft.com без прокси открывается, а домен их «дочки» – почему-то нет)*
</details>

<details>
    <summary>Исключения</summary>

- google.com
- gstatic.com

*(эти домены __не нужны__ для ускорения YouTube, но были зачем-то добавлены автором «ультимативного конфига»)*
</details>

## «И чё с этим делать?»
1. Открываете Clash Verge
1. Переходите в раздел Профили
1. Тыкаете Правой кнопкой мыши по своему профилю – Редактировать правила
1. Нажимаете сверху Дополнительно, копируете из моего файла правила и вставляете
1. Сохраняете и переключаете режим проксирования сначала на Прямой, а потом обратно на Правила, чтобы изменения подхватились
1. ???
1. PROFIT!!1

> [!CAUTION]
> **Ни в коем случае** не качайте большие файлы с включённым «ультимативным конфигом»! Держите под рукой обыкновенный конфиг с точками выхода из РФ, который не требует регистрации, и используйте его в глобальном режиме!

## Что ещё нужно сделать:
- Накидать сайтов, которые блокируют соединения с российских IP-адресов со **своей** стороны
- Добавить **больше** сайтов, попавших в опалу из-за прессинга CDN CloudFlare *(aka «ловушка 16 КБ»)*
