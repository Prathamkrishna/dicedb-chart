DICEDB HELM CHART [![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/dicedb-chart)](https://artifacthub.io/packages/search?repo=dicedb-chart)

What is Dice DB? DiceDB is an in-memory, real-time, and reactive database with Redis and SQL support optimized for modern hardware and building real-time applications. Refer: https://dicedb.io/

Steps to install:

helm repo add dicedb-chart https://prathamkrishna.github.io/dicedb-chart/

helm install my-dicedb dicedb-chart/dicedb --version 0.1.0
