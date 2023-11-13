# restart-q4-2023

## Week 1

### Week 1 - Day 1

- Installation

### Week 1 - Day 2

- OSI Layers - fundamentals
- Layer 1 - Physical
- Layer 2 - Data Link
- Hub vs. Router
- IPv4 vs. IPv6
- Local Network vs. Wide Area Network
- Layer 3 - NETWORK
- Binary -> Decimal conversion
- Decimal -> Binary conversion
- Private IPv4 address classes - class A, class B, class C
- Subnet masking - subnet division

### Week 1 - Day 3

- Route Tables
- ARP address resolution protocol
- IP Routing on Layer 3
- Layer 3 problems
- Layer 4 - Transport
- TCP vs. UDP
- TCP segments
- TCP 3 ways handshakes
- VSCode navigation & shortcut tutorials
- Markdown

### Week 1 - Day 4

- Encryption types & concept: Plaintext, Algorithm, Key (Symmetric, Public, Private), Ciphertext
- Symmetric Encryption
- Assymetric Encrytion
- Signing & Digital Signature
- Hashing
- Hashing vs. Symmetric Encryption
- Hashing Collision
- Weak Hashing vs. Strong Hashing
- Digital Signature of Hash Digest
- Data Keys, Master Key and key rotation
- Envelop Encryption
- End-to-End Encryption
- Git fundamental `git init`, `git add .`, `git commit -m "message"`, `git log`, `git checkout [commit hash]`
- Gitlense as VSCode extension

### Week 1 - Day 5

- `git diff [commit hash]` to compare the current with past commits
- `git tag "vX.Y.Z"`
- to change tag `git tag [new name] [old name]` then `git tag -d [old tag]`
- to list all tags `git tag -l`
- `git checkout tags/[tag]`
- `git checkout [branch]`
- create branch `git branch [branch name]`
- `git checkout [branch name]`, but before that you have to commit unstaged/staged changes
- `git merge [branch name]`, usually from `main` branch to pull changes to `main`
- `git branch -a --merged` to see past merged branches
- `git branch -d [branch name]`, to do delete branches, but this is not recommended
- Create Repo on Github > Clone to local > make local commit > push changes with `git push`

## Week 2 

### Week 2 - Day 1

- Python in REPL mode
- variable & value assignment
- integer `int`/float type `float`/string type `str`/boolean type `Boolean`
- checking type of variables/values via `type(var)`
- getting user input via prompt or terminal waiting via `input("input message")`
- string `my_str.upper()` and `my_str.lower()` function - in place
- list and nested list `[]`
- access item/item of lists
- check length of list/string via `len(my_list)` or `len(my_str)`
- list in place functions `my_list.append()`, `my_list.insert()`, `my_list.pop(index=0)`
- `my_list.sort()` (in-place) vs `sorted(my_list)` (copy)
- casting types `int(my_string)` or `str(my_float)`
- type hinting via type assignment
- no true constant problem in Python

### Week 2 - Day 2

- `tupple` type similar to `list` but it is immutable
- `sets` type, theory of how git works with `my_set.intersection(other_set)` & `my_set.difference(other_set)`
- dictionary `dict` type, `dict()` initialization
- `open()` to open files
- `boolean` type and logic evaluation
- `if elif else` flow control
- `while/break` loop

### Week 2 - Day 3

- `match/case` flow control
- `Enum` class via import `from enum import Enum`
- `match/case` and `Enum` combination for clean flow control
- `for` loop with `range(x)`
- `for` loop to iterate over a `list`
- `list` comprehension, quickly transform individual items of a `list` and put into a new `list`
- `for` loop with access to both `index` and `item` of a `list` with `for index,item in enumerate(my_list):`
- `for` loop with access to `key` and `value` of a `dict` with `for k,v in my_dict.items():`
- simple Queue data structure implementation via `list`
- `functions`, pure and impure functions, input/output, side effects
- in scope and out of scope

### Week 2 - Day 4

- `Exception` basics
- `assert`
- simple unit testing with `assert`
- `try/except` flow
- assign `Exception` into variable for further actions `except Exception as e`
- multiple `try/except` flows
- `try/except/else` flow

### Week 2 - Day 5

- `class` and `object` concepts
- creating `class` and `object`
- `class`: property, method, `__dict__` representation
- simple inheritance
- inheritance with custom property and method override

## Week 3

## Week 3 - Day 1

- sub-modules
- data transfer object theory (`DTO`)
- `dataclasses`
- `Pydantic` package
- `dataclasses` vs. `Pydantic`
- `@classmethod`
