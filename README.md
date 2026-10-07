<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" alt="Michelle Kanuri" width="100%">
</picture>

I work with data for a living, and I'm now building the engineering skills to move into data engineering properly. I like the part of the job that nobody sees when it goes well: checking that numbers are right, catching bad records before they reach a dashboard, and making a pipeline safe to re-run.

This profile holds my personal projects. Everything I do at work is private, so what you see here is what I build on my own time.

## What I'm working on

I'm putting together a portfolio of data engineering projects and applying to the Professional Master's in Big Data at SFU. My first public project is a real-time weather pipeline that I built to understand how streaming systems fail, and how to make them fail safely.

## Featured project

**[weather-streaming-pipeline](https://github.com/MichelleKanuri/weather-streaming-pipeline)**

Streams live weather and air quality readings for 50 cities through Kafka and Spark Structured Streaming. Every micro-batch is validated with Great Expectations, bad records go to a dead-letter queue instead of being dropped, and the sink is idempotent so a replay never creates duplicates. Results land in TimescaleDB and are shown in a Grafana dashboard that is generated from code.

The README is honest about what it does and doesn't guarantee, and about the mistakes I made along the way.

## Tools I use

![Python](https://img.shields.io/badge/Python-4A2C4A?style=flat-square&logo=python&logoColor=F6DDE2)
![Kafka](https://img.shields.io/badge/Kafka-8E6C8A?style=flat-square&logo=apachekafka&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-C98A9C?style=flat-square&logo=apachespark&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-8E6FB3?style=flat-square&logo=timescale&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4A2C4A?style=flat-square&logo=postgresql&logoColor=F6DDE2)
![Grafana](https://img.shields.io/badge/Grafana-D8A7B1?style=flat-square&logo=grafana&logoColor=4A2C4A)
![Docker](https://img.shields.io/badge/Docker-8E6C8A?style=flat-square&logo=docker&logoColor=white)
![Great Expectations](https://img.shields.io/badge/Great_Expectations-B79AD3?style=flat-square&logoColor=white)

## Say hello

- LinkedIn: [add your link here](https://www.linkedin.com/in/YOUR-LINKEDIN/)
- Email: add your address here
