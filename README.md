# ubuntu-18.10-config-pulse-audio-hd-sound
ubuntu 18.10 config pulse audio bass hd

sudo apt update && apt install speech-dispatcher libltdl  python-xdg  dotconf  libpulse  libao

/home/    user name   /.config/pulse

/etc/pulse проверить там не должно быть пустых любых папок , в случае если есть пустые папки то они должны быть срочно удалены иначе звука не будет

Потом обязательно перезагрузить компьютер

Осторожно звук очень четкий , возможно вам придётся выкинуть другие операционки и ждать OS 8.0

Надо выполнить speech-dispatcher и как то заставить те же приложения браузеры и всё остальное audio output speech-dispatcher за место того же AudioIPC Server допустим в firefox , звук сильно не реальный и изменит мнение что уже нельзя сделать сам звук лучше чем есть на каких либо операционных системах

То есть пока там в истерике бъются что лучше альса или пульса мы должны сделать audio output speech-dispatcher и слушать качественный звук в том же браузере и видео плеерах
