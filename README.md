# tracing-example

Quick example of using the [`tracing`](https://github.com/tokio-rs/tracing) crate that shaves some yaks.

```console
$ cargo run
Nov 21 13:38:21.913 INFO tracing_example: message: shaving yaks
Nov 21 13:38:21.914 WARN shave{yak: 3}: yak_events: message: could not locate yak!
Nov 21 13:38:21.914ERROR tracing_example: message: failed to shave yak!, yak: 3
```
