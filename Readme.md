Aby wykonać zadanie w pierwszej kolejności należy się zalogować na dockerhuba z poziomu konsoli.
Służy do tego polecenie:
```
docker login
```
Użytkownik jest poroszony o podanie nazwy użytkownika i hasła do dockerhuba.

W kolejnym kroku należy pobrać obraz nginx z repozytorium dockera.
Służy do tego polecenie:
```
docker pull nginx
```

Następnie należy otagować pobrany obraz.
Służy do tego polecenie:
```
docker tag nginx:latest kosier/lab12repo:lab12
```

Ostatnim krokiem do umieszczenia obrazu w dockerhubie jest jego push.
Służy do tego polecenie:
```
docker push kosier/lab12repo:lab12
```

Efektem wykonania powyższych poleceń jest obraz nginx, otagowany, dostępny w repozytorium dockerhub:

![image](https://github.com/SebTarLP/Lab12FullStack/assets/156203191/7cfbcb8c-b4dd-4d34-8027-d57e21a6ceb5)



