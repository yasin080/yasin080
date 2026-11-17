## Hi, I'm Yasin

Junior software engineer. I completed the **Common Core at 42 Urduliz**, where I learned
to program by building things from scratch in C and C++: a shell, an HTTP server, a
raycaster, containerised infrastructure and a multiplayer web game with a team.

I'm looking for a **junior software engineer** role.

### How I learned: 42

42 has no teachers and no classes. Each project comes with a goal and a set of rules,
and it's up to you to work out how to get there: reading documentation and man pages,
trying things, breaking them and asking other students. Every project is then reviewed
by peers, who test it and ask you to explain your code before it passes.

That way of working is what I take from 42: getting to a result on my own when there is
nobody to give me the answer, learning a new tool or language quickly when a project
needs it, and explaining and defending my decisions in code reviews.

42 was ranked the [3rd most innovative university in the world](https://www.42network.org/blog/breaking-news-42-ranks-3rd-worldwide-for-innovation/)
in the WURI rankings in 2025 and again in 2026.

### What I've built

**[revisatualquiler.es](https://www.revisatualquiler.es)** · my own product, in production (available in Spain only)

A web app that reviews Spanish rental contracts. You upload your contract, an LLM checks
each clause against the current law (LAU, Ley 12/2023 on housing) and you get a free
summary; the full report is sold as a PDF.
- Frontend: React 19, TypeScript, Vite, Tailwind CSS
- Backend: serverless functions on Vercel (Node.js, TypeScript), with an edge middleware
  that limits the service to Spain
- Data: Supabase (PostgreSQL), including a PL/pgSQL function for per-IP rate limiting
- LLM through the OpenRouter API, with the legal texts embedded in the prompt
- Payments with Stripe Checkout and webhooks; PDF reports generated with
  `@react-pdf/renderer` and sent by email with Resend

**[transcendence](https://github.com/yasin080/transcendence)** · team project (4 people), last project of the 42 Common Core

SlitherBomb, a real-time multiplayer 3D snake game with bombs, bots and spectators.
React + TypeScript and Babylon.js on the frontend, Laravel with WebSockets (Reverb) on
the backend, MariaDB and Redis, everything behind nginx with Docker Compose.

**[webserv](https://github.com/yasin080/Webserv)** · team project (3 people)

An HTTP/1.1 server in C++98: a single `poll()` loop with non-blocking sockets, virtual
hosts, CGI, uploads, chunked requests and an nginx-like configuration file.

**[minishell](https://github.com/yasin080/minishell)**

A small Bash-like shell in C: lexer and parser, pipes, redirections, heredoc, quoting,
variable expansion, builtins and signal handling.

**[Inception](https://github.com/yasin080/Inception)**

NGINX (TLS 1.2/1.3), WordPress with php-fpm and MariaDB, each in its own container built
from my own Dockerfiles, with Docker secrets, named volumes and a private network.

**[cub3d](https://github.com/yasin080/Cub3d)** · with a teammate

A Wolfenstein-style raycaster in C with miniLibX: DDA raycasting, textured walls,
collisions, minimap and a strict `.cub` map parser.

Also from 42: [philosophers](https://github.com/yasin080/Philosophers) (threads and
mutexes, the dining philosophers problem) and [push_swap](https://github.com/yasin080/push_swap)
(sorting with two stacks: 500 numbers in under 4,900 operations).

### Tools I've worked with

- **Languages:** C, C++, TypeScript, JavaScript, SQL, Bash
- **Web:** React, Vite, Tailwind CSS, Node.js serverless functions, REST APIs
- **Data and services:** PostgreSQL (Supabase), MariaDB, Stripe, Resend
- **Infrastructure:** Docker, Docker Compose, NGINX, Linux, Vercel, Git

### Contact

- Email: [yasinbahri08@gmail.com](mailto:yasinbahri08@gmail.com)
- LinkedIn: [linkedin.com/in/yasinbahri](https://www.linkedin.com/in/yasinbahri/)
