# hcc

## Build

- `$ stack build`
- `$ stack exec hcc-exe`

## Docker

### Build

- `$ docker build -t hcc .`

### Run

- `$ docker run -v "$PWD"/.:/home --rm -ti hcc`

## Assemble and Run

- `# gcc -o tmp tmp.s`

## make Asm file

- `# ./tmp`

## Run

- ex. `$ ./main '4'`

## TODO

- [ ] lexer error
