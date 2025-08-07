# Banking System (Object-Oriented Python)

This project is a refactored version of a banking system originally built using procedural programming, now redesigned with OOP principles in Python.

## Features

- Register new clients
- Create checking accounts
- Perform deposits and withdrawals
- Print transaction history
- List existing accounts

## Project Structure

- `Cliente` / `PessoaFisica`: handles client data and their accounts
- `Conta` / `ContaCorrente`: manages account operations
- `Transacao`, `Saque`, `Deposito`: represent bank transactions
- `Historico`: stores transaction history

## How to Run

1. **Clone this repository:**

```bash
git clone https://github.com/guimarobo/banking-system-oop.git
cd banking-system-oop
```

2. **Run the project:**
```bash
python banco_poo.py
```
or if, you're on macOS/Linux:
```bash
python3 banco_poo.py
```
