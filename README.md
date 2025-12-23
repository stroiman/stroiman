# Hi 👋

I'm Peter Strøiman, a senior freelance software developer with 25+ years of professional experience (yes, getting old).

I'm a long time TDD practitioner. Learning TDD has by far been the most important skill I've learned. But I was never taught TDD properly; I had to discover that for myself over the course of many years.

My most recent project, [Gost-DOM](https://github.com/gost-dom/browser) is born from the lack of a tool for a proper TDD process.

- 🔭 I’m currently working on
  - [Gost-DOM](https://github.com/gost-dom/browser) - A Headless browser for Go. Off-shot projects
    - [webref](https://github.com/gost-dom/webref) - Expose Web IDL specs as native Go objects (used for codegen in Gost-DOM)
    - [generators](https://github.com/gost-dom/generators) - Code generation helper library
    - [Surgeon](https://github.com/gost-dom/surgeon) - Surgically replace dependencies for test cases
  - [Muxify](https://github.com/stroiman/muxify) - A tool for managing TMUX sessions.
  - [Speed](https://github.com/stroiman/opam-speed) - An OCaml unit test framework. Ok, hasn't had updates for some time ...
- 🤔 I’m looking for help with Gost-DOM. Although I have a lot of web experience, having experts on the topic of how browsers work internally could help me avoid mistakes.
- ❤️ What I love
  - Open source software
  - Making solutions that solve real problems.
    - No, I don't give a s*** about requirement specs
    - I care about what the users actually needs, what problems they have that we can solve with software.
  - Finding simple solutions to complex problems
  - Eliminating unnecessary complexity
  - TDD - I believe this is the most important skill you can learn to increase productivity.
- 💬 Ask me about ...
  - Anything programming related
  - TDD - Too many get it wrong, making it hard to learn (you learn the wrong things)

## TDD

The fast feedback cycle allows you to work in small increments, discovering invalid assumptions early, and truncating an unproductive path.

Modern web development frameworks typically have live-reload functionality meaning, you see the changes as soon as you save your work.[^1] This is invaluable when working with UI code; as you get immediate visual feedback on every file save.

It's the feedback loop that's important; and that's the essence of TDD, setting up a feedback loop. But instead of a visual feedback loop; you set a set of logical expectations, something describing the desired _behaviour_ of the system, preferably with sub-second feedback.

The short feedback encourages short small increments, which in turn increases productivity. That is why TDD isn't just about preventing the feature today from breaking tomorrow. It is about working more effectively already from day one.

All the same, they allow you to refactor safely. You can extract abstractions when you discover them; or remove them when they are no longer useful.

## Gost-DOM

[Gost-DOM](https://github.com/gost-dom/browser) is my most ambitious open-source project to date, and was started, as I lacked a tool to provide fast and relevant feedback for [HTMX](https://htmx.org/) applications.

Gost-DOM is a headless browser written in Go, i.e., a Go module (or library) that produces a browser-like environment including a JavaScript engine. By cutting out the overhead of a real browser, Gost-DOM is so fast, that it can provide usefule feedback _while implementing the behaviour_ of web applications written in Go;

## Lover of Open-Source

The software development ecosystems has seen a dramatic change during my career. In the early days, development tools were typically commercial products, as were 3rd party components. Updates were months in between, and software was delivered on physical media, Compact Disk or even Floppy Disk. And you didn't get the source code.

Today, you can build higly scalable web applications, as well as native GUI applications, exclusively using free and open-source software. This is a dramatic change to the life a software developer;

I owe so much to open-source, and I do what I can to give something back!

---

[^1]: I remember working with NCrunch, a Visual Studio plugin that would execute your test suite as you were typing, didn't even need to save the files. Pretty awesome, but an unfortunate side effect was that we often forgot to save _after_ the test passed. This was a little too fast (Ps, if anyone from that company read this, and you still maintain the product. Run the tests; but don't show the result until the user saves. Gives the impression of an even faster test run).

<!--
**stroiman/stroiman** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
