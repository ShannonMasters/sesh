# sesh

Terminal sessions, written in Rust.

Built on gRPC and unix sockets.

> **Warning**       
> This is a work in progress, and may contain some bugs.        

## Demo


https://user-images.githubusercontent.com/38540736/233831581-c925ea27-6ec3-4bf7-bcb9-11e7b9c4d974.mp4


## Installation

### From source

Release:

`cargo install --locked term-sesh`

Git:

`cargo install --git https://github.com/willothy/sesh`

## Usage:

See the `help` subcommand or [MANUAL.md](https://github.com/willothy/sesh/blob/main/MANUAL.md) for more info.


## Integration:

<details>
<summary><a href="https://starship.rs/">Starship</a></summary>

```toml
[custom.sesh]
command = "echo $SESH_NAME"
when = ''' test "$SESH_NAME" != "" '''
format = '\(sesh [$output]($style)\)'
```

</details>
