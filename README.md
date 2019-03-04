# ubuntu-18.10-config-pulse-audio-hd-sound
ubuntu 18.10 config pulse audio bass hd

sudo apt update && apt install speech-dispatcher 

Перенесите свой конфиг pulse куда нибудь на всремя , возьмите конфиг pulse из архива и поместите его на то время только как можно быстее пока там не образовался конфиг пульсы заново или можно выполнить kill pulseaudio

/home/    user name   /.config/pulse

sudo su rm -rf /home/    user name   /.cache

/etc/pulse проверить там не должно быть пустых любых папок , в случае если есть пустые папки то они должны быть срочно удалены иначе звука не будет

Потом обязательно перезагрузить компьютер

Firefox about:config создать строку speech-dispatcher с параметром enable выглядеть должно как здесь https://github.com/Griggorii/ubuntu-18.10-config-pulse-audio-hd-sound/blob/master/speech-dispatcher%20firefox.png

Осторожно звук очень четкий , возможно вам придётся выкинуть другие операционки и ждать OS 8.0 , пока не понятно может он даёт какие то гармоники или через него что то проходит я так и не понял , звук получается более насыщенным и пружинистым , даже в наушниках перепонках будет играть по взрослому будто это оборудование цап высокой четкости, а может включаются какие кодеки которые пока ещё не известны миру и они уже парралелют аудио дорожку на более большее количество аудио аутпут-а , но опять же если это у меня создался такой аудио кодек без всякого программирования , но с поехавшей в будущее программой то по названию всё равно видно что это speech-dispatcher даёт это воздействие.

Запуск срабатывает так speech-dispatcher

Включается в браузере примерно так переберанием команд если у вас DE Budgie то удобно потом его смотреть в аудио устройствах боковой панели справа

&& firefox speech-dispatcher

&& speech-dispatcher firefox

&& firefox=speech-dispatcher

&& spd-say окно



Открыть firefox

Открыть какой нибудь муз канал убедившись что в аудио появились такие устройства три штуки с названием speech-dispatcher или можно полистать сайты и они могут появиться сами я пока это явление не выловил , но факт фактом speech-dispatcher может передавать аудиопоток. Примерно картинка https://github.com/Griggorii/ubuntu-18.10-config-pulse-audio-hd-sound/blob/master/speech-dispatcher.png

Вот ещё пакет из серии http://archive.ubuntu.com/ubuntu/pool/main/s/speech-dispatcher/speech-dispatcher-audio-plugins_0.8.8-6ubuntu1_i386.deb


Надо выполнить speech-dispatcher и как то заставить те же приложения браузеры и всё остальное audio output speech-dispatcher за место того же AudioIPC Server допустим в firefox , звук сильно не реальный и изменит мнение что уже нельзя сделать сам звук лучше чем есть на каких либо операционных системах

То есть пока там в истерике бъются что лучше альса или пульса мы должны сделать audio output speech-dispatcher и слушать качественный звук в том же браузере и видео плеерах

Вроде его зависимости libltdl  python-xdg  dotconf  libpulse  libao
