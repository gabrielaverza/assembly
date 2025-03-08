# Programas Assembly MIPS / MIPS Assembly Programs

[English version below](#english-version)

Este repositório contém três programas escritos em Assembly MIPS, desenvolvidos para demonstrar conceitos de programação de baixo nível e manipulação de dados.

### Programas Incluídos

1. **dataDeNascimento.asm**: Programa para validação e formatação de datas de nascimento.
2. **mensagemCriptografada.asm**: Programa para criptografar mensagens usando substituição de caracteres.
3. **mensagemCriptografadaEstendida.asm**: Versão estendida do programa de criptografia, com funcionalidade adicional para descriptografar mensagens.

### Requisitos

- Emulador MIPS ou simulador, como MARS (MIPS Assembler and Runtime Simulator) ou SPIM
- Software para compilação e execução de código Assembly MIPS

### Instruções de Uso

#### Instalação do MARS (recomendado)

1. Baixe o MARS em [Missouri State University](http://courses.missouristate.edu/kenvollmar/mars/)
2. Instale e execute o Java Runtime Environment (JRE)
3. Execute o MARS com: `java -jar Mars.jar`

#### Execução dos Programas

1. Abra o MARS (ou seu emulador MIPS preferido)
2. Carregue o arquivo .asm desejado
3. Compile o programa (F3 no MARS)
4. Execute o programa (F5 no MARS)

### Detalhes dos Programas

#### 1. dataDeNascimento.asm

**Descrição**: Programa que solicita ao usuário uma data de nascimento (dia, mês e ano) e valida se está dentro de intervalos aceitáveis.

**Funcionalidades**:
- Validação de dias (1-31)
- Validação de meses (1-12)
- Validação de anos (1900-2021)
- Formatação da data (DD/MM/AAAA)

**Exemplo de Uso**:
```
Entre com o dia (DD): 15
Entre com o mes (MM): 7
Entre com o ano (AAAA): 1990

Data de Nascimento: 15/07/1990
```

#### 2. mensagemCriptografada.asm

**Descrição**: Programa que lê uma mensagem do usuário e a criptografa usando um esquema de substituição de caracteres.

**Esquema de Substituição**:
- Espaço → 0
- a/A → 1
- r/R → 2
- e/E → 3
- o/O → 4
- m/M → 5
- h/H → 6
- l/L → 7
- s/S → 8
- p/P → 9
- 0 → Espaço
- 1 → A
- 2 → R
- 3 → E
- 4 → O
- 5 → M
- 6 → H
- 7 → L
- 8 → S
- 9 → P

**Exemplo de Uso**:
```
Insira a mensagem: hello world
Numero total de caracteres: 11
Mensagem Criptografada: 63774042427d
```

#### 3. mensagemCriptografadaEstendida.asm

**Descrição**: Versão estendida do programa de criptografia, com funcionalidade adicional para descriptografar mensagens após inserir uma senha correta.

**Funcionalidades adicionais**:
- Solicitação de senha após a criptografia
- Descriptografia da mensagem se a senha correta for fornecida (123456)

**Exemplo de Uso**:
```
Insira a mensagem: hello world
Numero total de caracteres: 11
Mensagem Criptografada: 63774042427d
Insira a senha: 123456
Mensagem Original: hello world
```

---

<a name="english-version"></a>
This repository contains three programs written in MIPS Assembly, developed to demonstrate low-level programming concepts and data manipulation.

### Included Programs

1. **dataDeNascimento.asm**: Program for validating and formatting birth dates.
2. **mensagemCriptografada.asm**: Program for encrypting messages using character substitution.
3. **mensagemCriptografadaEstendida.asm**: Extended version of the encryption program, with additional functionality to decrypt messages.

### Requirements

- MIPS emulator or simulator, such as MARS (MIPS Assembler and Runtime Simulator) or SPIM
- Software for compiling and running MIPS Assembly code

### Usage Instructions

#### Installing MARS (recommended)

1. Download MARS from [Missouri State University](http://courses.missouristate.edu/kenvollmar/mars/)
2. Install and run Java Runtime Environment (JRE)
3. Run MARS with: `java -jar Mars.jar`

#### Running the Programs

1. Open MARS (or your preferred MIPS emulator)
2. Load the desired .asm file
3. Compile the program (F3 in MARS)
4. Run the program (F5 in MARS)

### Program Details

#### 1. dataDeNascimento.asm (Birth Date)

**Description**: Program that prompts the user for a birth date (day, month, and year) and validates if it is within acceptable ranges.

**Features**:
- Day validation (1-31)
- Month validation (1-12)
- Year validation (1900-2021)
- Date formatting (DD/MM/YYYY)

**Usage Example**:
```
Entre com o dia (DD): 15
Entre com o mes (MM): 7
Entre com o ano (AAAA): 1990

Data de Nascimento: 15/07/1990
```

#### 2. mensagemCriptografada.asm (Encrypted Message)

**Description**: Program that reads a message from the user and encrypts it using a character substitution scheme.

**Substitution Scheme**:
- Space → 0
- a/A → 1
- r/R → 2
- e/E → 3
- o/O → 4
- m/M → 5
- h/H → 6
- l/L → 7
- s/S → 8
- p/P → 9
- 0 → Space
- 1 → A
- 2 → R
- 3 → E
- 4 → O
- 5 → M
- 6 → H
- 7 → L
- 8 → S
- 9 → P

**Usage Example**:
```
Insira a mensagem: hello world
Numero total de caracteres: 11
Mensagem Criptografada: 63774042427d
```

#### 3. mensagemCriptografadaEstendida.asm (Extended Encrypted Message)

**Description**: Extended version of the encryption program, with additional functionality to decrypt messages after entering a correct password.

**Additional Features**:
- Password request after encryption
- Message decryption if the correct password is provided (123456)

**Usage Example**:
```
Insira a mensagem: hello world
Numero total de caracteres: 11
Mensagem Criptografada: 63774042427d
Insira a senha: 123456
Mensagem Original: hello world
```
