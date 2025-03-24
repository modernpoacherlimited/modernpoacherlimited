# Jonathan Perry

<img src="./jonathan-perry.png" alt="A profile picture of Jonathan Perry" width="25%" />

## Senior/Lead Full-Stack Developer

I have thirty years experience building websites and have been creating **JavaScript** applications since 1999. I am the Lead and Founder at **Modern Poacher**.

I use **EcmaScript** and **TypeScript** with **React** and **Node**.

You can [email me directly](mailto:jonathanperry@jonathanperry.com) or [message me on LinkedIn](https://linkedin.com/pub/jonathan-perry/0/327/822).

My [CV is available on Dropbox](https://www.dropbox.com/scl/fi/p7xxztow6wmkrvjlhtxn4/Jonathan-Perry.docx?rlkey=9f2chcljox2o7wa2wwhecvwbr&st=1vpamj2h&dl=0).

## Modern Poacher Limited

The [Modern Poacher](https://github.com/modernpoacher) organisation has projects which are related to or derived from the **Zashiki Karakuri** platform.

The [Sequence Media](https://github.com/sequencemedia) organisation has the majority of my public projects.

Several projects for **Modern Poacher** (including the Back Office **Karakuri** app) are _private_.

**Zashiki Karakuri** _produces_, _exchanges_, and _validates_ `JSON` documents.

It's used to gather data from _users_ and direct them through a _journey_ to resolution.

---

### React

Both [`shinkansen-cogs`](https://github.com/modernpoacher/shinkansen-cogs) and [`shinkansen-sprockets`](https://github.com/modernpoacher/shinkansen-sprockets) were begun around 2014 for **Zashiki** (which is the Front Office part of the **Zashiki Karakuri** platform). At the start of 2025 I improved their _type definitions_ as well as their tests in [Jest](https://jestjs.io/). I have used _versions_ of them on several other projects and even forked them, to `cogs` and `sprockets` respectively, where there are some useful changes which aren't compatible with **Zashiki**. (Be aware that depending on time and need the forked projects may not be in sync with the originals.)

### Node

[Zashiki](https://github.com/modernpoacher/zashiki) is the _core_ from which are derived _implementations_. Currently it is written _for_ [Hapi](https://hapi.dev/) but it could be adapted for [Express](https://expressjs.com/).

- The **React** implementation uses Ajax requests
- The **GDS** implementation does not use Ajax at all and _instead_ depends on `HTTP` `GET` and `POST` requests

Form Data is transformed into `JSON` documents and `JSON` documents transformed back into Form Data with [`shinkansen-transmission`](https://github.com/modernpoacher/shinkansen-transmission).

### Jest

I use **Jest** for component testing, sometimes _in conjunction_ with [Mocha](https://mochajs.org/). I also use [Testing Library](https://testing-library.com/) but have depended on _instance_ and _snapshot_ testing for so long that it didn't make sense to migrate those suites so instead I implemented  _instance_ and _snapshot_ testing for **Testing Library**. Which I'm sure will get me sent to **Jest** jail.

- [`react-component-instance`](https://github.com/modernpoacher/react-component-instance)
- [`react-component-snapshot`](https://github.com/modernpoacher/react-component-snapshot)

---

- [Email me directly](mailto:jonathanperry@jonathanperry.com)
- [Message me on LinkedIn](https://linkedin.com/pub/jonathan-perry/0/327/822)
- My [CV is available on Dropbox](https://www.dropbox.com/scl/fi/p7xxztow6wmkrvjlhtxn4/Jonathan-Perry.docx?rlkey=9f2chcljox2o7wa2wwhecvwbr&st=1vpamj2h&dl=0)
