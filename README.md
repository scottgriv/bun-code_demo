# Bun Code Demo

Bun is an all-in-one `JavaScript` and `TypeScript` runtime & toolkit designed for speed, complete with a bundler, test runner, and Node.js-compatible package manager.

For example, with only a few lines of code, you can get a HTTP server up and running with `Bun`:
```javascript
const server = Bun.serve({
    port: 3000,
    fetch(request) {
      return new Response("Welcome to Bun!");
    },
  });
  
  console.log(`Listening on localhost:${server.port}`);
```

## Getting Started
1. Install the Bun CLI globally using `npm install -g @bun/bun`
2. Create a new project using `bun new my-project`
3. Change directory to the new project using `cd my-project`
4. Install dependencies using `bun install`
5. Run the project using `bun run`
6. Open the project in your favorite editor and start coding!

## References
- [Bun](https://bun.sh/) - Bun's official website
- [Bun Documentation](https://bun.sh/docs) - Documentation for Bun

## License
- This project is released under the terms of the **Unlicense**, which allows you to use, modify, and distribute the code as you see fit. 
- The Unlicense removes traditional copyright restrictions, giving you the freedom to use the code in any way you choose.
- For more details, see the [LICENSE](LICENSE) file in this repository.

## Credit
**Author:** Scott Grivner <br>
**Email:** scott.grivner@gmail.com <br>
**Website:** [scottgrivner.dev](https://www.scottgriv.dev) <br>
**Reference:** [Main Branch](https://github.com/scottgriv/bun-code_demo) <br>