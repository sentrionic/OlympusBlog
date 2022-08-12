# OlympusBlog

**OlympusBlog** is a blog website that's heavily inspired by [Medium](https://medium.com/) and the [Realworld](https://github.com/gothinkster/realworld) project. It's a way for me to learn new frameworks and languages in a familiar setting.

# Implementations

**Backend**

- [NestJS](https://github.com/sentrionic/OlympusNest)
- [.NET](https://github.com/sentrionic/OlympusNET)
- [Spring Kotlin Edition](https://github.com/sentrionic/OlympusSpring)
- [Ktor](https://github.com/sentrionic/OlympusKtor)
- [Gin](https://github.com/sentrionic/OlympusGin)
- [Phoenix](https://github.com/sentrionic/OlympusPhoenix) (Unfinished)
- [Spring Java Edition](https://github.com/sentrionic/OlympusBlogSpring)

**Frontend**

- [NextJS](https://github.com/sentrionic/OlympusClient)

**Mobile**

- [Android](https://github.com/sentrionic/OlympusAndroid) (Unfinished)

## Specification

All backends follow the same REST API specs.
All of them use PostgreSQL as their database and sessions stored in Redis for authentication.
Similarly, all of them upload files to the same AWS S3 Bucket.

For a collection of all the endpoints with expected inputs and outputs check out `api`. The given file is used to test all new stacks.

`DataGen` contains a small React site to quickly generate a random amount of users and articles and is also a good way to check session authentication and CORS settings.
