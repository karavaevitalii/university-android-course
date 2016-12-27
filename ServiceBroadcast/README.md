# Домашнее задание

Время на выполнение 8 недель, до 23 ноября 2016.

В данном домашнем задании предлагается набить руку в написании сервисов и BroadcastReceiver-ов. Предлагается реализовать загрузку картинки по какому-либо событию в системе, чтобы, при запуске пользовательского интерфейса, она отобразилась моментально.

Что нужно сделать:

1. Написать код, загружающий большую картинку из сети и сохраняющий её на телефоне - 1 балл.
2. Реализовать activity, показывающую эту картинку, если она уже загружена, либо текст ~«Не загружено» в противном случае - 2 балла.
3. Написать сервис, вызывающий код загрузки картинки, если это необходимо - 3 балла.
4. Написать BroadcastReceiver на любое событие, которое можно легко получить на эмуляторе, который по этому событию будет запускать сервис - 2 балла
5. Опрятность кода - 2 балла.

6. Обновление activity автоматически, если загрузка картинки завершилась уже после её отображения - 2 балла сверху.