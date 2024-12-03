<div align=center>
<h1>Sqlite Cleaner</h1>
</div>


<div align="center">
        <img src="https://img.shields.io/badge/Rust-dea584?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
    <img src="https://img.shields.io/badge/Sqlite-Cleaner-53a863?style=for-the-badge" alt="Database Cleaner" />
    <img src="https://img.shields.io/badge/Version-1.0.0-informational?style=for-the-badge" alt="Version" />
</div>

## Description

DBMS Cleaner is a program made to be run to clean the database. It will
reduce the storage of the database and optimise all tables except system tables. It is a simple and efficient way to
keep your
database clean and optimised without having to do it manually. It is a great way to keep your database running in the
best conditions possible. Using Rust, it is compatible with all platforms and can be run on any server or application.

## Features

<ul>
<li>Reduce storage of the database</li>
<li>Optimise all tables except system tables</li>
<li>Simple and efficient way to keep your sqlite database clean</li>
<li>Compatible with all platforms</li>
<li>Maintain your database in the best conditions possible</li>
<li>Don't require any dump or backup</li>
<li>Don't modify your files configuration</li>
<li>Easily run on any server or application</li>
<li>Easy to use</li>
</ul>

## Platforms & Requirements

<div align="center">
<img src="https://img.shields.io/badge/OS-MacOS-informational?style=flat&logo=apple&logoColor=white&color=53a863" alt="MacOS" />
<img src="https://img.shields.io/badge/OS-Linux-informational?style=flat&logo=linux&logoColor=white&color=53a863" alt="Linux" />
<img src="https://img.shields.io/badge/OS-Windows-informational?style=flat&logo=windows&logoColor=white&color=53a863" alt="Windows" />
</div>

<div align="center">
<img src="https://img.shields.io/badge/Rust-1.83+-informational?style=flat&logo=rust&logoColor=white&color=53a863" alt="Rust" />
<img src="https://img.shields.io/badge/Cargo-informational?style=flat&logo=rust&logoColor=white&color=53a863" alt="Cargo" />
</div>

## Installation

To run the program :

1. Clone the repository:

```bash
git clone https://github.com/Maxime-Cllt/SqliteCleaner.git
```

2. Build the program:

```bash
cargo build --release
```

3. Execute the program:

### MacOS & Linux

```bash
cd target/release/SqliteCleaner "database.db"
```

### Windows

```bash
cd target/release/SqliteCleaner.exe "database.db"
```

## Notes

- Time complexity: O(n) where n is the number of tables in the database
- Don't clean triggers, stored procedures, functions, and views
- May not reduce much storage but don't cost much time to run and can be run frequently
- Require some privileges to connect to the database and to perform the cleaning

## See Also

<ul>
<li><a href="https://rust-lang.org" target="_blank">Rust</a></li>
<li><a href="https://sqlite.org" target="_blank">Sqlite</a></li>
</ul>

