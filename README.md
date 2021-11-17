# speedrun-number
Speedrun a specific number.<br>
A random number is continously generated by start and end values you set. If it hits your specific number the loop breaks and the times it iterated is printed out.
Have fun beating your and your friends high scores.

## Usage
On Linux download the [latest release](https://github.com/minced1/speedrun-number/releases) and run `./speedrun-number`. <br>
_Windows usage coming soon._<br>
_macOS usage coming perhaps._<br>
You will get asked three questions. Answer them by typing any integer value and pressing Enter.

## Dependencies
|Dependency|Description|Version|License|Type|
|----------|-----------|-------|-------|----|
|[rand@^0.8.0](https://github.com/rust-random/rand)|A Rust library for random number generation|0.8.0|Apache|production|

When built with cargo, the dependencies are automaticly pulled from [crates.io](https://crates.io/).

## Compiling
### Install build tools
On Linux and macOS run `curl https://sh.rustup.rs -sSf | sh` in the command line.<br>
On Windows download and run [rustup-init.exe](https://win.rustup.rs).

### Build code
In the local repository run 
`cargo run`
to build and run the code<br>
or run
`cargo build`
to just build the code.<br>
Your binary will be in `LOCATION_OF_REPOSITORY/speedrun-number/target/debug/`.

## TODO
- [x] Change hard coded values to soft coded ones
- [X] Add validation for values
- [ ] Add possibility to store and sort values from one session
