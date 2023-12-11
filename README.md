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

### Week 3 - Day 1

- sub-modules
- data transfer object theory (`DTO`)
- `dataclasses`
- `Pydantic` package
- `dataclasses` vs. `Pydantic`
- `@classmethod`
 
### Week 3 - Day 2

- Regex, Regex visualizer, Regex testing
- Integration theory: messaging, file sharing, RPC (includes `REST API` & `gRPC`)
- `OSI Layers` revision
- `JSON` serialization & `JSON` parsing
- `Postman API Client`
- Testing some public API such as `http.cat`

### Week 3 - Day 3

- API theory: `Data Transfer Object` or `DTO`
- Building API on top of `Pydantic Schema` classes
- `HTTP Codes`
- `FastAPI input auto-parser` via Pydantic classes
- `PUT` API building
- `GET` API building
- Distinguish 4 ways to provide data: `Header`, `Body`, `Path Parameters`, `Query Parameters`
- `API auto-docs`

### Week 3 - Day 4

- `API auto-docs` best practices - including always type hint your API returns
- Adding basic persistence for API
- Continuation with API: `PUT`, `GET`, `DELETE`, and `GET` multiple items

### Week 3 - Day 5

- VSCode debugger setup
- Debugging techniques
- Dependency injection theory
- Testing theory: unit testing, integration testing, end-end testing, smoke testing, regression testing...
- Pytest unit testing `pytest`, `pytest -s`, `pytest --vl`
- FastAPI TestClient `from fastapi.testclient import TestClient`
- unit testing API

## Week 4

### Week 4 - Day 1

- Pytest Fixture
- Using `@pytest.fixture` to create new instance of API Client for each test, or set default data
- Parametizing test functions `@pytest.mark.parametrize`
- Data Access Object theory `DAO`

### Week 4 - Day 2

- Install DB client within VSCode
- Installing SQLite
- Playing with Sakila.db
- SQL `SELECT`, `COUNT`, `DISTINCT`, `GROUP BY`, `WHERE`, `LIMIT`, `OFFSET` with logic operators
- SQL `JOIN` 
- SQL `INSERT INTO ... VALUES`
- SQL `UPDATE`

### Week 4 - Day 3

- More SQL `UPDATE`
- Python virtual environment `venv`
- SQLModel - as a Relational Object Mapping tool (ORM)
- Revisit DTO, DAO theory
- Building simple SQL model
- Building simple API with automatic DTO <-> DAO conversion

### Week 4 - Day 4

- SQL `primary key` vs `index key` vs `compound index key`
- SQL `foreign key` constraint
- Building APIs with SQLModel ORM
- Learning why we should have dedicated DTO & DAO layers, shouldn't rely on automatic conversion

### Week 4 - Day 5

- Mainly to discuss Assignment 1

## Week 5

### Week 5 - Day 1

- Intro to Cloud Computing
- `IaaS` vs. `PaaS` vs. `SaaS`
- Platform engineering responsibility

### Week 5 - Day 2

- Advantages of Cloud Computing
- What is AWS?
- AWS Pricing Model and unit cost charges
- FinOps
- Total Cost of Ownership comparison
- AWS `API` vs. `Management Console` vs. `CLI` vs. `SDK`

### Week 5 - Day 3

- AZ, and why use 3 AZs
- Region
- Local services vs. Global services (domain name services DNS, IAM, CDN)
- POP = Edge Locations + Edge Caches
- CDN
- Storage Services overview
- Networking Services overview
- Security Services overview
- Management Services overview - Landing Zone and why split AWS accounts
- Integration Services overview

### Week 5 - Day 4

- Shared responsibility model examples (Self managed DB vs. RDS)
- S3 Service concepts 
- S3 Tiers
- S3 DNS overview
- S3 Cost charges model
- EC2 recommended usecases
- Create EC2 instance 
  - AMI & Golden Image practice
  - Instance Type, Instance family & size
  - Network settings, high availability setups
  - IAM Role, Instance profile
  - User data script
  - Instance Store vs. EBS drives
  - Tag & ABAC
  - TBC...

### Week 5 - Day 5

- EC2 labs
- Linux commands labs
- Stateful vs. Stateless firewalls
- Security Groups
- Practical ways to use Security Groups
- How multiple component groups work together via ALB, dedicated Security Group for different application component groups

## Week 6

### Week 6 - Day 1

- How DNS works, TLD, Name Server, Zone, Zone File
- Traversing DNS Tree
- DNS Records: NS, A, AAAA, Alias (unique to AWS), CNAME, TXT
- Drawio, multiple drawing exercises

### Week 6 - Day 2

- Public & Private IP
- IGW
- Security Group
- NACL
- ALB
- NATGW
- Subnets division & intro to VPC design

### Week 6 - Day 3

- More networking protocols and standard TCP ports
- Comprehensive VPC design
  - How many application tiers (ALB/NATGW, web, app, db...)
  - How many AZs
  - Design the subnets
  - Design public facing tiers ALB/NATGW/Internet GW
  - Design route tables
  - Design the security group

### Week 6 - Day 4

- Security Fundamentals
- Prevention methods: Networking
  - NACL
  - SG
  - WAF
  - IPS
  - Subnetting, zoning
  - AWS Network Firewall's implementation
- Prevention methods: PKI
  - DNS
  - CA
  - DNSSEC (more later)
  - Use of CA's certificates
  - Application of ACM

### Week 6 - Day 5

- Prevention methods: Data Security
  - Data at rest vs. Data in transit
  - Symmetric vs. Asymmetric vs. Hybrid encryption revision
  - KMS (API only + multi-tenancy) vs. CloudHSM (normally only PKCS 11 or other low level interfaces)
  - Hashing
  - Key algorithm available
  - Never use same key pairs for both encryption & signing
  - Import key materials to KMS
  - Provide CloudHSM with API interface of KMS
  - CloudHSM deployment model
- Prevention methods: IAM
  - IAM Policy
  - IAM Role
  - IAM User
  - IAM Group
  - Condition & permission boundary example
