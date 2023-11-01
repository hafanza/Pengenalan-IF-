# 1.1 Latar Belakang
ActiviTask helps you manage tasks easily. It's a user-friendly tool for creating and to-do lists. Simply add tasks, delete them off when they're done. It boosts productivity and keeps you on track with your daily activities. Elevate your task management with ActiviTask.

I followed an iterative or incremental development methodology in creating my application by repeatedly going through the steps of design, development, and testing by using MIT App Inventor

erDiagram
    PENGGUNA ||--o{ POSTINGAN : MEMPOSTING
    PENGGUNA {
      string username
      string password
    }

    PENGGUNA_LAIN ||--|{ POSTINGAN : MENYUKAI
    PENGGUNA_LAIN {
      string username

    }

    POSTINGAN {
      image foto
      string username_pengguna
      int jumlahLike
    }
    PENGGUNA ||--|{ PENGGUNA_LAIN : MENGUNJUNGI_PROFIL

