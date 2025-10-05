# Plugin Docker
## Alias

| Alias | Perintah | Deskripsi |
| :--- | :--- | :--- |
| **dbl** | `docker build` | Membangun *image* dari *Dockerfile* |
| **dcin** | `docker container inspect` | Menampilkan informasi rinci tentang satu atau lebih *container* |
| **dcls** | `docker container ls` | Mendaftar semua *container* *docker* yang sedang berjalan |
| **dclsa** | `docker container ls -a` | Mendaftar semua *container* yang sedang berjalan dan yang sudah dihentikan |
| **dib** | `docker image build` | Membangun *image* dari *Dockerfile* (sama dengan `docker build`) |
| **dii** | `docker image inspect` | Menampilkan informasi rinci tentang satu atau lebih *image* |
| **dils** | `docker image ls` | Mendaftar *image* *docker* |
| **dipu** | `docker image push` | Mendorong (*push*) *image* atau *repository* ke *registry* jarak jauh |
| **dipru** | `docker image prune -a` | Menghapus semua *image* yang tidak direferensikan oleh *container* mana pun |
| **dirm** | `docker image rm` | Menghapus satu atau lebih *image* |
| **dit** | `docker image tag` | Menambahkan nama dan *tag* ke *image* tertentu |
| **dlo** | `docker container logs` | Mengambil *log* dari *container* *docker* |
| **dnc** | `docker network create` | Membuat *network* baru |
| **dncn** | `docker network connect` | Menghubungkan *container* ke *network* |
| **dndcn** | `docker network disconnect` | Memutuskan hubungan *container* dari *network* |
| **dni** | `docker network inspect` | Mengembalikan informasi tentang satu atau lebih *network* |
| **dnls** | `docker network ls` | Mendaftar semua *network* yang diketahui oleh *daemon* mesin, termasuk yang mencakup banyak *host* |
| **dnrm** | `docker network rm` | Menghapus satu atau lebih *network* |
| **dpo** | `docker container port` | Mendaftar pemetaan *port* atau pemetaan spesifik untuk *container* |
| **dps** | `docker ps` | Mendaftar semua *container* *docker* yang sedang berjalan |
| **dpsa** | `docker ps -a` | Mendaftar semua *container* yang sedang berjalan dan yang sudah dihentikan |
| **dpu** | `docker pull` | Menarik (*pull*) *image* atau *repository* dari *registry* |
| **dr** | `docker container run` | Membuat *container* baru dan memulainya menggunakan perintah yang ditentukan |
| **drit** | `docker container run -it` | Membuat *container* baru dan memulainya dalam *shell* interaktif |
| **drm** | `docker container rm` | Menghapus *container* yang ditentukan |
| **drm!** | `docker container rm -f` | Memaksa penghapusan *container* yang sedang berjalan (menggunakan SIGKILL) |
| **dst** | `docker container start` | Memulai satu atau lebih *container* yang sudah dihentikan |
| **drs** | `docker container restart` | Memulai ulang satu atau lebih *container* |
| **dsta** | `docker stop $(docker ps -q)` | Menghentikan semua *container* yang sedang berjalan |
| **dstp** | `docker container stop` | Menghentikan satu atau lebih *container* yang sedang berjalan |
| **dsts** | `docker stats` | Menampilkan statistik *streaming* waktu nyata untuk *container* |
| **dtop** | `docker top` | Menampilkan proses yang sedang berjalan dari suatu *container* |
| **dvi** | `docker volume inspect` | Menampilkan informasi rinci tentang satu atau lebih *volume* |
| **dvls** | `docker volume ls` | Mendaftar semua *volume* yang diketahui oleh *docker* |
| **dvprune** | `docker volume prune` | Membersihkan *volume* yang menggantung (*dangling volumes*) |
| **dxc** | `docker container exec` | Menjalankan perintah baru di *container* yang sedang berjalan |
| **dxcit** | `docker container exec -it` | Menjalankan perintah baru di *container* yang sedang berjalan dalam *shell* interaktif |

---

# Docker-compose
## Alias

| Alias | Perintah | Deskripsi |
| :--- | :--- | :--- |
| **dco** | `docker-compose` | Perintah utama *Docker-compose* |
| **dcb** | `docker-compose build` | Membangun *container* |
| **dce** | `docker-compose exec` | Mengeksekusi perintah di dalam *container* |
| **dcps** | `docker-compose ps` | Mendaftar *container* |
| **dcrestart** | `docker-compose restart` | Memulai ulang *container* |
| **dcrm** | `docker-compose rm` | Menghapus *container* |
| **dcr** | `docker-compose run` | Menjalankan perintah di dalam *container* |
| **dcstop** | `docker-compose stop` | Menghentikan *container* |
| **dcup** | `docker-compose up` | Membangun, (membuat ulang), memulai, dan melampirkan (*attach*) ke *container* untuk suatu layanan |
| **dcupb** | `docker-compose up --build` | Sama seperti `dcup`, tetapi membangun *image* sebelum memulai *container* |
| **dcupd** | `docker-compose up -d` | Sama seperti `dcup`, tetapi dimulai sebagai *daemon* |
| **dcupdb** | `docker-compose up -d --build` | Sama seperti `dcup`, tetapi membangun *image* sebelum memulai *container* dan dimulai sebagai *daemon* |
| **dcdn** | `docker-compose down` | Menghentikan dan menghapus *container* |
| **dcl** | `docker-compose logs` | Menampilkan *log* dari *container* |
| **dclf** | `docker-compose logs -f` | Menampilkan *log* dan mengikuti (*follow*) *output* |
| **dclF** | `docker-compose logs -f --tail0` | Hanya mengikuti (*follow*) *log* terbaru |
| **dcpull** | `docker-compose pull` | Menarik (*pull*) *image* dari suatu layanan |
| **dcstart** | `docker-compose start` | Memulai *container* |
| **dck** | `docker-compose kill` | Membunuh *container* |