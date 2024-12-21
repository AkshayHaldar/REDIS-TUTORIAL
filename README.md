# REDIS-TUTORIAL [![My Skills](https://simpleskill.icons.workers.dev/svg?i=redis)](https://redis.io/) [![My Skills](https://skillicons.dev/icons?i=redis)](https://redis.io/)
Redis - Remote Dictionary Server . Built by Salvatore Sanfilippo (known as antirez) in 2009. **Redis Labs** (Previously knew as **Garantia Data**) , is the organisation which maintains redis.

# Major changes in 2024 💡
Maybe some of us has got a recent spiced up news of redis's sudden license change which created an internal conflict within the organisation. Redis changed its previous license **BSD 3-Clause Model** to **Dual-License Model** (Interested Peeps can check out this news on web). What this change caused , is a born of a new project - **Valkey** (supported by Linux Foundation also)

# Redis vs Valkey ⚡
Developers who built redis under previous license came in **Valkey**. Redis under BSD , was maintained  till version 7.4x (7.4.6) which ended in October 2024. From November 2024 , Redis 8.0x series started which obeys Dual-License . On the other hand , Valkey started from v7.5x by the OG developers of redis , under BSD license.

# Features of Redis 🕶️
Have a look on the points below :
- **In-Memory**: Redis is an In-Memory product , means it stores user's data in RAM . Also we know that RAM is volatile and only necessary datas are stored inside ram which got removed when the computer shuts down. That happens with Redis also.

- **Database or not**: A contoversial point and many will consider Redis as a database also , what its documentation says **Data Structure Store - [link](https://redis.io/docs/latest/develop/get-started/data-store/)**. Although we can use redis as a document-based database but for that we need **redis-cloud** - ([link](https://redis.io/docs/latest/develop/get-started/document-database/)) . At this point you can utilize redis-cloud but remember , **redis is primarliy storing data in your device's RAM , then if you have chosen Redis-cloud , you may shift your datas to a cloud instance (sounds like mongodb-atlas but a little different)**. Else you can use **redis-om (https://redis.io/blog/introducing-redis-om-client-libraries/)** for giving a proper structure to raw datas.

- **Lua Scripting**: Lua is an lightweight language , majorly used for embedded programming. In Redis, Lua scripting enables users to write scripts that can perform complex operations directly on the server side. This means that instead of sending multiple commands from a client to the server, **users can bundle these commands into a single Lua script and execute it with one call.**

- **Data Structures and Atomicity**: 

- **Pub-Sub Architechture**:

# Installation 📋

# RESP (Redis Serialization Protocol) 💻

# Data Structures ⛓️
