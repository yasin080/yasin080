## Yasin Bahri · Junior Software Engineer

I build software end to end: from a Unix shell and an HTTP server in C/C++ to
[revisatualquiler.es](https://www.revisatualquiler.es), a web app I designed, built and
launched on my own, with real payments in production.

Common Core completed at **42 Urduliz**. Based in Bilbao. Looking for a junior software
engineer role.

📫 [yasinbahri08@gmail.com](mailto:yasinbahri08@gmail.com) · [LinkedIn](https://www.linkedin.com/in/yasinbahri/)

### How I learned: 42

42 was ranked the [3rd most innovative university in the world](https://www.42network.org/blog/breaking-news-42-ranks-3rd-worldwide-for-innovation/)
(WURI, 2025 and 2026). There are no teachers and no classes: each project is a goal and a
set of rules, and I had to work out the rest from documentation, man pages, trial and
error and other students. Some projects are individual and others are built in teams of
up to four, and every one is graded by peers who test it and make me defend my code.

What that means for a team: I can get to a working result on my own when I need to, I'm
used to sharing a codebase with teammates (splitting the work, branches, pull requests
and code review), and I pick up new tools quickly.

### What I've built

**[revisatualquiler.es](https://www.revisatualquiler.es)** · solo project, in production (available in Spain only)

Checks Spanish rental contracts against the law. Users upload their contract, an LLM
reviews every clause against the LAU and Ley 12/2023, and they get a free summary and a
paid PDF report.
- React 19 + TypeScript + Tailwind, serverless API on Vercel, Supabase (PostgreSQL)
- Stripe Checkout with webhooks, PDF generation and transactional email (Resend)
- Per-IP rate limiting in PL/pgSQL and edge middleware to restrict access by country

**[transcendence](https://github.com/yasin080/transcendence)** · team of 4, final 42 Common Core project

SlitherBomb, a real-time multiplayer 3D snake game with bombs, bots and spectators
(React, Babylon.js, Laravel, WebSockets, Docker).

**[webserv](https://github.com/yasin080/Webserv)** · team of 3

An HTTP/1.1 server in C++98 that handles every connection in a single `poll()` loop:
virtual hosts, CGI, uploads, chunked requests and an nginx-style config file.

**[minishell](https://github.com/yasin080/minishell)**

A small Bash-like shell in C: lexer and parser, pipes, redirections, heredoc, quoting,
variable expansion, builtins and signal handling.

**[Inception](https://github.com/yasin080/Inception)**

NGINX (TLS 1.2/1.3), WordPress with php-fpm and MariaDB, each in its own container built
from my own Dockerfiles, with Docker secrets, named volumes and a private network.

**[cub3d](https://github.com/yasin080/Cub3d)** · team of 2

A Wolfenstein-style raycaster in C with miniLibX: DDA raycasting, textured walls,
collisions, minimap and a strict `.cub` map parser.

Also from 42: [philosophers](https://github.com/yasin080/Philosophers) (threads and
mutexes, the dining philosophers problem) and [push_swap](https://github.com/yasin080/push_swap)
(sorting with two stacks: 500 numbers in under 4,900 operations).

### Tools I've worked with

- **Languages:** C, C++, TypeScript, JavaScript, SQL, Bash
- **Web:** React, Vite, Tailwind CSS, Node.js serverless functions, REST APIs, WebSockets (Laravel Reverb)
- **Data and services:** PostgreSQL (Supabase), MariaDB, Stripe, Resend
- **Infrastructure:** Docker, Docker Compose, NGINX, Linux, Vercel, Git

### Contact

- Email: [yasinbahri08@gmail.com](mailto:yasinbahri08@gmail.com)
- LinkedIn: [linkedin.com/in/yasinbahri](https://www.linkedin.com/in/yasinbahri/)
