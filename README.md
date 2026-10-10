# Driss Laktaf

Software engineering student at **42 Luxembourg**, looking for a first role as a developer.

I learn by building things that have to actually run — a scheduler that does not
deadlock, a game that holds its frame rate, a retrieval pipeline that returns the
right chunk. Nearly everything below comes from projects I took from an empty
folder to something that works, and had to defend line by line.

## Stack

### Systems and low-level

`C` `POSIX threads` `Make` `GDB`

Reimplemented a subset of the C standard library, a variadic `printf` with full
format parsing, and a stack-sorting solver optimised for move count under a
restricted instruction set. Built a concurrency simulator with FIFO and EDF
scheduling over a min-heap priority queue. Manual memory management throughout,
no leaks.

### Python

`Python 3` `pytest` `mypy` `flake8` `pygame-ce` `PyInstaller`

Type-hinted, linted and unit-tested by default. A complete Pac-Man built on a
drawing layer deliberately restricted to MLX-equivalent primitives, where every
shape — lines, discs, ellipses, filled polygons — is rasterised by hand from
`put_pixel`, then packaged into a standalone executable. Also a maze generator
and a routing optimiser over a capacitated network.

### Go

`Go` `net` `IPC` `concurrency`

An IPC message queue with named topics, prefix-filtered subscriptions and
resumable committed offsets, covered by 27 test files. Also a multiplayer text
adventure served over a hand-written TCP protocol, standard library only.

### Machine learning

`constrained decoding` `tokenisation` `information retrieval`

Built a JSON-constrained decoder around a small language model, so its output
matches a function schema by construction rather than by prompting, with a
byte-level BPE tokeniser written from the vocabulary file rather than pulled
from a library. Also a retrieval pipeline combining lexical and semantic search
over a large codebase.

### Infrastructure

`Docker` `Linux` `Debian` `UFW` `SSH` `LVM` `git`

Multi-container infrastructure built from custom images. A hardened Debian
server with encrypted LVM, firewall rules, a strict sudo and password policy,
AppArmor and scripted monitoring.

## Selected work

- [agent-smith](https://github.com/driss-lktf/agent-smith) — a code-agent that writes Python, runs it in a sandbox we built, and fixes real bugs from SWE-bench Verified
- [call-me-maybe](https://github.com/driss-lktf/call-me-maybe) — natural language to JSON function calls, valid by construction rather than by prompting
- [rag](https://github.com/driss-lktf/rag) — retrieval-augmented generation over a large codebase, combining lexical and semantic search
- [pac-man](https://github.com/driss-lktf/pac-man) — the arcade game on a drawing layer restricted to MLX-equivalent primitives, every shape rasterised by hand
- [codexion](https://github.com/driss-lktf/codexion) — concurrency simulation with FIFO and EDF scheduling over a min-heap priority queue

## Currently

Working through the 42 common core. Open to internships and junior positions in
Luxembourg and the Grande Région.

Contact details are on my GitHub profile.
