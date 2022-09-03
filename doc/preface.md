# Preface

Welcome to my Game Boy Advance experiment notes.
The content here covers the journey writing a Game Boy Advance (GBA) game from scratch.
It uses the [Rust programming language][rust] and aims to not use any dedicated libraries.
Instead, the whole thing is covered in detail, so that the hardware and software is well-understood.

This book is written alongside my own experiments with the GBA platform.
I try to write everything important down in a style, that should be somewhat readable and hopefully also enjoyable.
The intention is, that this is something like a mix of a tutorial and a walktrough.
Note, that earlier chapters might contain errors¹ or misdirections, that are fixed later one.
This is related to the way this book is written: it is like a diary of the GBA experiments.

The book is written and the code is developed in [this repository](https://github.com/jfrimmel/gba-experiments).
If you encounter something, that is unclear to you, please open an [issue] over there, so this can be improved.
If something can be improved, either wording or code, feel free to open an [issue] as well or even a [pull request] right away.
If you find a severe error¹ or a short-coming please also report an [issue], as I want this to be free of actual errors.

[rust]: https://rust-lang.org
[issue]: https://github.com/jfrimmel/gba-experiments/issues/new
[pull request]: https://github.com/jfrimmel/gba-experiments/compare

> ¹: There are two kinds of errors at play here.
> First there are the hard errors with plain wrong or misleading information.
> Those should certainly be fixed, e.g. via a [pull request].
> There are, however, also errors in the sense of misguided ideas and wrong directions when developing something.
> I tend to keep those, as they suite the "diary"-style of this book.
