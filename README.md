# studyrecord

レイヤー構成
```
studyrecord/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/studyrecord/
│   │   │       ├── controller/
│   │   │       ├── service/
│   │   │       ├── mapper/        ← ★MyBatisの場所
│   │   │       ├── entity/        ← 勉強の記録クラス
│   │   │       └── StudyrecordApplication.java
│   │   └── resources/
│   │       ├── application.yml    ← 設定ファイル
│   │       └── mapper/            ← XMLマッピングファイル
├── build.gradle
├── Dockerfile
├── docker-compose.yml            ← Dockerで全部うごかす用
└── README.md
```
