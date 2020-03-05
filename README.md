# MIRCO
a very programmable MIDI thing.

## ???

Install `bison` and `flex`.

### Arch:

`bash
pacman -S bison flex
`

Run `make`.

Run `./a.out`.

Edit `syntax.txt`!

## Syntax 

Define new sequence:

`

sequence seq(arg1, arg2) {
    arg1, C4, D4, arg2
}

`

Map to Midi input note:

`

C4 : seq(F4, D4)
default: seq(G4, D4)

`

or autoplay:

`

auto: seq(G4, D4)

`
