# How to Run CVFS

## Prerequisites

Install a C compiler such as **GCC**.

## 1. Clone the Repository

```bash
git clone https://github.com/TanayaRohidasKhaire/CVFS.git
```

Move into the project directory:

```bash
cd CVFS
```

## 2. Compile

```bash
gcc CVFS.c -o CVFS
```

## 3. Run

### Windows

```bash
CVFS.exe
```

### Linux / macOS

```bash
./CVFS
```

## 4. Example Commands

Create a file:

```text
creat Demo.txt 3
```

List files:

```text
ls
```

Write data:

```text
write 3
```

Read data:

```text
read 3 10
```

Display file information:

```text
stat Demo.txt
```

Delete a file:

```text
unlink Demo.txt
```

Exit:

```text
exit
```

## File Permissions

| Value | Permission   |
| ----: | ------------ |
|   `1` | Read         |
|   `2` | Write        |
|   `3` | Read + Write |
