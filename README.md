# ubuntu-18.10-config-pulse-audio-hd-sound
ubuntu 18.10 config pulse audio bass hd

sudo apt update && apt install speech-dispatcher 

Перенесите свой конфиг pulse куда нибудь на всремя , возьмите конфиг pulse из архива и поместите его на то время только как можно быстее пока там не образовался конфиг заного

/home/    user name   /.config/pulse

sudo su rm -rf /home/    user name   /.cache

/etc/pulse проверить там не должно быть пустых любых папок , в случае если есть пустые папки то они должны быть срочно удалены иначе звука не будет

Потом обязательно перезагрузить компьютер

Осторожно звук очень четкий , возможно вам придётся выкинуть другие операционки и ждать OS 8.0

Запуск срабатывает так speech-dispatcher

Включается в браузере примерно так переберанием команд если у вас DE Budgie то удобно потом его смотреть в аудио устройствах боковой панели справа

&& firefox speech-dispatcher

&& speech-dispatcher firefox

&& firefox=speech-dispatcher

Открыть терминал и забить команду && EGL_SYNC_TO_VBLANK=0 DISPLAY=:0.0 firefox

Открыть какой нибудь муз канал убедившись что в аудио появились такие устройства три штуки с названием speech-dispatcher


Надо выполнить speech-dispatcher и как то заставить те же приложения браузеры и всё остальное audio output speech-dispatcher за место того же AudioIPC Server допустим в firefox , звук сильно не реальный и изменит мнение что уже нельзя сделать сам звук лучше чем есть на каких либо операционных системах

То есть пока там в истерике бъются что лучше альса или пульса мы должны сделать audio output speech-dispatcher и слушать качественный звук в том же браузере и видео плеерах

Вроде его зависимости libltdl  python-xdg  dotconf  libpulse  libao
