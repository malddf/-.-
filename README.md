Чтобы запустить приёмник:

gcc receiver.c -o r && ./r

Чтобы отправить сигнал:

gcc emitter.c -o e && ./e PID SIGNAL

Где

PID - число, которое отобразилось в консоли после запуска приёмника

SIGNAL - значение: ( SIGUSR1 | SIGUSR2 )
