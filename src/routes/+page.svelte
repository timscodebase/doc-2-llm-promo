
<svelte:head>
  <title>Doc 2 LLM.txt - Documentation Tool</title>
  <link rel="stylesheet" href="/app.css" />
</svelte:head>

<main class="container">
  <header>
    <img src="/logo.png" alt="Docs 2 LLM Logo" />
    <p>
      Effortlessly generate <a href="https://svelte.dev/llms-small.txt">Svelte-style</a> documentation for your projects with doc-2-llm - the NPM package that bridges your code to LLM-friendly formats!</p>
    <a class="github-link" href="https://github.com/timscodebase/doc-2-llm"><iconify-icon icon="line-md:github-twotone"></iconify-icon><pre>See the code</pre>
    </a>
  </header>

  <section>
    <h2>Why <code>doc-2-llm</code>?</h2>
    <p>
      Inspired by Svelte's own documentation format (like <a href="https://svelte.dev/llms-small.txt">llms-small.txt</a>), <strong>doc-2-llm</strong> ensures your project's documentation is not only human-readable but also optimized for language models. This makes it easier to integrate with AI tools, maintain consistency with Svelte's standards, and future-proof your documentation for advanced development workflows.
    </p>
  </section>

  <section>
    <h2>Features</h2>
    <ul>
      <li>Generates <code>project_documentation.md</code> with a table of contents: Navigate your project's structure with ease, complete with code blocks for clarity.</li>
      <li>Creates <code>[project-name]-llm.txt</code> in the "llms-small.txt" format: Ensures compatibility with Svelte's trusted documentation style, perfect for LLM processing.</li>
      <li>Preserves code whitespace for readability: Your code looks as intended, even in documentation, making it easier to review and maintain.</li>
      <li>Supports multiple file types: Works seamlessly with Svelte, JS, TS, JSON, CSS, HTML, and more.</li>
      <li>Easy to install and use: Global or local installation with simple commands, and run it in any project directory.</li>
    </ul>
  </section>

  <section>
    <h2>Why LLM-Friendly Documentation?</h2>
    <p>
      LLM-friendly documentation allows your project to be easily processed and understood by language models, enabling features like automated summaries, code analysis, and integration with AI-driven development tools. With <strong>doc-2-llm</strong>, your documentation is future-proof and ready for the next generation of development tools.
    </p>
  </section>

  <section>
    <h2>How to Use</h2>
    <p>Install globally with npm:</p>
    <pre><code>npm install -g doc-2-llm</code></pre>
    <p>Run in your project directory:</p>
    <pre><code>doc-2-llm</code></pre>
    <h3>Or</h3>
    <p>From anydirectory:</p>
    <pre><code>doc-2-llm 'path/to/project'</code></pre>
    <p>
      After running, you'll find: 
      <br>
      <code>project_documentation.md</code>
      <br>
      (a comprehensive markdown file with a table of contents and code blocks) 
    </p>
    <h4 style="margin: 0; padding: 0;">And</h4>
    <p>
      <br>
      <code>[project-name]-llm.txt</code>
      <br>
      (a text file with each file's content prefixed by <code>/// file: [path]</code>, preserving whitespace and formatted like Svelte's <a href="https://svelte.dev/llms-small.txt">llms-small.txt</a>).
    </p>
  </section>

  <footer>
    <p>Created by <a href="https://github.com/timscodebase">Tim Smith</a></p>
    <p>Released under the <a href="https://github.com/timscodebase/doc-2-llm/blob/main/LICENSE">MIT License</a></p>
    <p>Partners in Code {new Date().getFullYear()}</p>
  </footer>
</main>