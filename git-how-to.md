как создать ssh ключ
    settings -> add new key -> вставить строчку из файла, созданного с помощью ssh-keygen -t ed25519 -C "your_email@example.com"
как добавить ключ в аккаунт на GitHub
    settings -> add new key -> вставить строчку из файла 
как склонировать репозиторий
    git clone "ssh url"

How to BRANCH

переходим в репозиторий кента:
    cd /home/b04-206/Repositories/Vasilev/
создаем ветку:
    b04-206@raspberrypi:~/Repositories/Vasilev $ git branch Golenskikh
перезодим в ветку:
    b04-206@raspberrypi:~/Repositories/Vasilev $ git checkout Golenskikh
Видим и радуемся:
        Switched to branch 'Golenskikh'
