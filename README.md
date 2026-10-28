# Caio Ariel

```console
caioariel@github:~$ fastfetch

     .-----------.       MAJOR      ->  Computer Science
     | >_        |       NAME       ->  Caio Ariel
     |           |       COLLEGE    ->  Mackenzie (Dec/2027)
    /|___________|\      STACK      ->  Java (Spring Boot), C# (.NET), C/C++, Python
   /______[__]_____\     STATUS     ->  CNPq Researcher
                         RESEARCH   ->  HPC, Distributed Systems
                         LOCATION   ->  São Paulo, Brazil

caioariel@github:~$ █
```

Backend engineering and distributed systems, with a research background in high-performance computing.

`Java` `Spring Boot` `C#` `.NET` `C` `C++` `Python` `PostgreSQL` `Docker` `AWS` `Linux`

> **Research:** CNPq undergraduate research fellow, investigating proactive fault tolerance for tightly-coupled HPC workloads on AWS Spot Instances (checkpoint/restart, MPI ULFM, heartbeats).

---

## Projects

**[Overwatch Tracker](https://github.com/caiosaraiv1/overwatch-tracker)** — `Java 21` `Spring Boot` `JPA` `Flyway`  
REST API to record Overwatch matches and compute per-hero statistics (winrate, average eliminations, damage, healing). Matches are created atomically with their nested hero performances in a single transaction. The project uses versioned database migrations, feature-based package organization, and structured error handling through domain-specific exceptions and a global handler.

**[AniTrack](https://github.com/caiosaraiv1/anitrack)** — `C#` `.NET` `EF Core` `PostgreSQL`  
Anime tracking API that searches a public anime API, manages a personal watch list, and tracks episode progress. It resyncs with the external API when the user's progress exceeds the known episode count and falls back to local data when the API is unavailable. Persistence uses EF Core with Fluent API mapping and migrations.

**[OSPF Network Simulator](https://github.com/caiosaraiv1/simulador-ospf)** — `C++` `Docker` `CMake`  
Distributed simulator of the OSPF routing protocol with multithreaded router nodes and Dijkstra shortest-path convergence. Chaos injection is used for resilience testing across mesh topologies of up to 50 routers.

**[Telegram Deal Monitor](https://github.com/caiosaraiv1/telegram-deal-monitor)** — `Python` `AWS EC2` `Docker`  
Event-driven bot using Telethon (MTProto) to parse real-time deals across 6+ Telegram channels with zero polling overhead. It is containerized and deployed on AWS EC2, running 24/7.

---

## Contact

[linkedin.com/in/caioariel](https://www.linkedin.com/in/caioariel) · caio.ariel@outlook.com
