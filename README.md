## Hi there 👋

I'm a senior freelance software developer with 25+ years of professional experience (yes, getting old).

I'm a long time TDD practitioner. Learning TDD has by far been the most important skill I've learned. But it took many years, because I was never taught what TDD really is about. I had to discover for myself.

My most recent project, [Go-DOM](https://github.com/stroiman/go-dom) is born from the lack of a tool for a proper TDD process.

- 🔭 I’m currently working on
  - [Go-DOM](https://github.com/stroiman/go-dom) - A Headless browser for Go.
  - [Muxify](https://github.com/stroiman/muxify) - A tool for managing TMUX sessions.
  - [Speed](https://github.com/stroiman/opam-speed) - An OCaml unit test framework. Ok, hasn't had updates for some time ...
- 🤔 I’m looking for help with Go-DOM. Although I have a lot of web experience, having experts on the topic of how browsers work internally could help me avoid mistakes.
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

The most important factor for developer productivity is a fast feedback cycle. For user interface work, the feedback is visual. Make a change to code, look at the resulting web page, PDF document, generated email, console output from the CLI command, or whatever you are building.

The fast feedback cycle allows you to work in small increments, detecting wrong assumptions early, and truncating an unproductive path. Modern web development frameworks typically have live-reload functionality meaning, you see the changes as soon as you save your work.[^1]

For the vast majority of your code, the feedback is about the outcome of a certain function meets your expectations. The true nature of TDD is setting up the feedback loop, allowing you to work in small increments, making small changes that work as expected, and extracting sensible abstractions when you descover them, or remove abstractions that have become unnecessary over time.

That is why TDD isn't just about preventing the feature today from breaking tomorrow. It is about working more effectively already from day one. 

## Go-DOM

My most ambitious open-source project is [Go-DOM](https://github.com/stroiman/go-dom), a headless browser written in Go to test Go web applications with embedded JavaScript. The browser executes JavaScript using V8 (but a native Go solution is also in the works).

It is specifically written with the intention to support a fast TDD feedback loop when building web applications with Go and [HTMX](https://htmx.org/), a tech combination that is gaining in popularity.

I believe this would be an extremely useful tool for a lot of projects in the future, and I would be very grateful for support, e.g. through the sponsoship program.

### Lover of Open-Source

The landscape has changed dramatically since I started. Back then, you would normally have to pay for development environments. 3rd party components were typically also something you needed to purchase. Updates were months in between, and software was delivered on CD. I think something was still delivered on floppy when I started.

Today, you can build higly scalable web applications, as well as native GUI applications using open-source software.

This is a dramatic change to the landscape, and I owe so much to the open-source community.

It can only be natural that I do my part.

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
