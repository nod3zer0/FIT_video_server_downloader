# video server downloader
 takovej jednoduchej script co jsem si napsal, když jsem se učil bash. Bude tam asi pár chyb, ale celkem to usnadní stahování přednášek. 
## download-playlist.sh
 - je potreba vyplnit prihlasovaci udaje v login.sh
 - stahne kompletni predmet
 - je potreba stahovat do slozky ve ktere nejsou zadne soubory *.mp4* jelikoz je program pouziva k zjisteni progresu
 - spusteni ./download-playlist "url predmetu na video serveru" "cesta kam ulozit soubory"
 
 - pri přerušení stahování si script zvládne při opětovvném spuštění zjistit odkud má pokračovat podle počtu mp4 souborů v cílové složce

### known issues
 - script z nějakého důvodu přeskočí 1. přednášku. 
