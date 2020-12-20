- Cara untuk menginstall melalui GitHub
Gunakan perintah dibawah ini untuk dapat mengclone/mendownload data dari repository github :

```sh
$ git clone https://github.com/kuniken456/195410105
$ cd 195410105
```

- Cara untuk menjalankan
Gunakan perintah dibawah ini untuk membuat image, serta menjalankan container dengan image `195410105-kevin` :

```sh
$ docker build -t 195410105-kevin ./
$ docker run -dit --name 195410105-kevin-res -p 3000:80 195410105-kevin
```

Kemudian buka browser Anda dengan url `http://locahost:3000` agar dapat melihat hasil.
- Melalui Docker Hub
- Tutorial Menjalankan
Gunakan perintah dibawah ini untuk mengambil image dari dockerhub, serta menjalankan container dengan image `195410105-kevin` :
```sh
$ docker run -dit --name 195410105-kevin-res -p 3000:80 axylon/195410105-kevin:latest
```
Selanjutnya buka browser Anda dengan url `http://locahost:3000` agar dapat melihat hasil.