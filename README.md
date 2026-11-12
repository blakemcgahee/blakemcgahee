# Blake McGahee

I'm finishing a B.S. in Computer Science at the University of Florida (December 2026). Most of my recent work is backend development: database backed APIs, authentication and access control, and automated testing. The projects below also cover compilers, computer architecture, and data structures in TypeScript, Java, C++, and Python.

## Skills

| Area | Skills |
| :--- | :--- |
| **Backend and Databases** | REST API design, PostgreSQL, schema design and migrations, authentication, access control |
| **Data Structures and Algorithms** | AVL trees, linked lists, graph algorithms, backtracking, iterative and recursive algorithms |
| **Compiler Design** | Lexing, parsing, AST construction, semantic analysis, code generation |
| **Systems and Architecture** | Cache simulation (LRU and FIFO), memory hierarchy, C++ |
| **Analysis** | Big O analysis, comparative performance testing, data compression (RLE) |
| **Languages** | TypeScript, Java, C++, Python, SQL |

## Featured Projects

### 1. Health Hub (in progress)
**Repository:** Private (UF Senior Design team project, source available on request)
**Status:** In active development, pilot demo planned for December 2026

A full stack patient engagement platform for independent practices and mid market clinics, built by a team of three in a TypeScript monorepo. Patients book and manage appointments, clinical staff chart encounters and write notes, and administrators manage staff, financials, and audit history. I own the backend, database, and data layer.

| Area | What I Built |
| :--- | :--- |
| **Database** | PostgreSQL schema covering identity, scheduling, clinical, billing, and audit data, with forward and rollback migrations |
| **Authentication** | Login and session management with Argon2 password hashing and hashed session tokens that can be revoked |
| **Access Control** | Role based permissions for patients, clinical staff, and administrators, enforced on the server and covered by negative tests |
| **Scheduling** | Provider availability and booking logic, with database constraints that prevent double booking and overlapping appointments |
| **Testing** | 390+ automated tests with Vitest across API routes and database behavior |
| **Data** | Deterministic synthetic seed data generator for demo and test datasets |

**Stack:** TypeScript, Fastify, PostgreSQL 16, Docker, Vitest, GitHub Actions

### 2. PLC Compiler
**Repository:** [github.com/blakemcgahee/PLC_Project](https://github.com/blakemcgahee/PLC_Project)

A full compiler pipeline built from scratch in Java. It takes a custom programming language through tokenization, parsing, type checking, and execution.

| Stage | Component | Responsibility |
| :--- | :--- | :--- |
| **Lexing** | Lexer | Tokenizes raw source code |
| **Parsing** | Parser | Builds an AST with recursive descent parsing |
| **Analysis** | Analyzer | Performs semantic analysis and type checking |
| **Generation** | Generator | Emits target code from the validated AST |
| **Execution** | Interpreter | Runs the program directly |

### 3. Cache Simulation
**Repository:** [github.com/blakemcgahee/Cache-Simulation](https://github.com/blakemcgahee/Cache-Simulation)

A cache simulator and performance analysis that measures hit rates as cache size, associativity, and replacement policy change.

| Parameter | Values Examined | Goal |
| :--- | :--- | :--- |
| **Cache Size** | 256 B to 16,384 B | See how hit rate scales with capacity |
| **Associativity** | Direct mapped to fully associative | Weigh added complexity against fewer conflict misses |
| **Replacement Policy** | LRU, FIFO | Compare how well each manages blocks |

### 4. Search Algorithm Performance Study
**Repository:** [github.com/blakemcgahee/the-searchers-final-project](https://github.com/blakemcgahee/the-searchers-final-project)

A comparison of search algorithms that measures and visualizes their runtime across different datasets and constraints.

## Data Structures and Algorithms

| Project | Language | Description | Link |
| :--- | :--- | :--- | :--- |
| **AVL Trees** | C++ | Self balancing binary search tree with insertion, deletion, and rotations that keep operations at $O(\log n)$. | [Code](https://github.com/blakemcgahee/C-CodingProjects/tree/main/AVL%20Trees) |
| **Comparing Search Algorithms** | C++ | Runtime comparison of search algorithms across different data sizes and structures. | [Code](https://github.com/blakemcgahee/C-CodingProjects/tree/main/Comparing%20Search%20Algorithms) |
| **Linked List** | C++ | Linked list implementation with traversal, insertion, and deletion. | [Code](https://github.com/blakemcgahee/C-CodingProjects/tree/main/Linked%20List) |
| **Simplified PageRank** | C++ | Ranks the nodes of a directed graph by iterating over its link structure. | [Code](https://github.com/blakemcgahee/C-CodingProjects/tree/main/Simplified%20PageRank%20Algorithm) |
| **Image Processing** | C++ | Reads and writes image files and applies pixel level transformations to them. | [Code](https://github.com/blakemcgahee/C-CodingProjects/tree/main/Image%20Processing) |
| **RLE and Console Graphics** | Python | Run length encoding for lossless image compression, with conversion between raw, encoded, and string formats and a terminal display for the results. | [Code](https://github.com/blakemcgahee/pythonProjects/tree/main/Project%202A%20RLE) |

## Games

| Project | Language | Description | Link |
| :--- | :--- | :--- | :--- |
| **Minesweeper** | C++ | Minesweeper on a 2D grid with recursive neighbor reveal and game state handling. | [Code](https://github.com/blakemcgahee/C-CodingProjects/tree/main/Minesweeper) |
| **Sudoku Generator** | Python | Generates and solves Sudoku puzzles with backtracking and constraint checking. | [Code](https://github.com/blakemcgahee/pythonProjects/tree/main/Project%204) |
| **Blackjack** | Python | Text based Blackjack with player input, game state, and random card dealing. | [Code](https://github.com/blakemcgahee/pythonProjects/tree/main/Project1) |
| **Pakudex** | Python | Object oriented collection manager using custom classes and inheritance. | [Code](https://github.com/blakemcgahee/pythonProjects/tree/main/Project%203) |

## Contact

**Email:** blakemcgahee.bm@gmail.com
