<p align="center">
	<img align="center" src="https://avatars.githubusercontent.com/u/97196209?s=200&v=4"  />
	<br>
    <h1 align="center">🦕 Astrodon  </h1>
    <p align="center">Desktop App Framework (not there yet!) for Deno, based on <a href="https://tauri.studio/">Tauri</a></p>
</p>

[![Discord Server](https://discordapp.com/api/guilds/928673465882513430/widget.png)](https://discord.gg/adYYqHHDBA)
[![deno module](https://shield.deno.dev/x/astrodon)](https://deno.land/x/astrodon)
![deno compatibility](https://shield.deno.dev/deno/^1.20.2)

---

### 😎 Features

- Create webview windows with your own title and URL
- Bidirectional communication between your frontend and backend
- Compile your apps as executables and even make installers
- And all that you get with Deno, e.g, TypeScript out of the box...

A lot is still missing, but we will get there!

### 🎁 Demo

to-do

### 📜 To-do

- [ ] Unit tests
- [x] Cross-platform compiling (missing: Apple Silicon)
- [ ] Typescript checking in the background (astrodon-build's Develop should
      manage this)
- [ ] Pass permission and arguments as flags and also put them in the executable
      metadata
- [x] Organize project a little bit better (e.g move dependencies to deps.ts)
- [x] A real-world app example
- [ ] Update the templates
- [ ] Match `deno_runtime` version (and also things like `Deno.build`) with
      Deno's releases
- [ ] Implement Web Workers
- [ ] Schematize and create plugin system
- [ ] Organize configs by usage hierarchy (e.g. global.icon -> build.icon)
- [ ] Register custom system URI protocols (installer)
- [ ] Cross process reactivity module (plugin)
- [ ] Cross process store module (plugin)
- [ ] Env variable manager and injection for builds (plugin)
- [ ] Cli command `astrodon clean` to remove cached runtimes

### 👩‍💻 Development

Requisites:

- If you want to compile the binaries yourself: install the tauri dependencies
  as indicated in
  [Tauri's Guide](https://tauri.studio/en/docs/getting-started/intro).

to-do

MIT License
