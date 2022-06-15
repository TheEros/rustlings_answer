# rustlings 🦀❤️

```csv
Name             	Path                                          	Status
intro1           	exercises/intro/intro1.rs                     	Done
intro2           	exercises/intro/intro2.rs                     	Done
variables1       	exercises/variables/variables1.rs             	Done
variables2       	exercises/variables/variables2.rs             	Done
variables3       	exercises/variables/variables3.rs             	Done
variables4       	exercises/variables/variables4.rs             	Done
variables5       	exercises/variables/variables5.rs             	Done
variables6       	exercises/variables/variables6.rs             	Done
functions1       	exercises/functions/functions1.rs             	Done
functions2       	exercises/functions/functions2.rs             	Done
functions3       	exercises/functions/functions3.rs             	Done
functions4       	exercises/functions/functions4.rs             	Done
functions5       	exercises/functions/functions5.rs             	Done
if1              	exercises/if/if1.rs                           	Done
if2              	exercises/if/if2.rs                           	Done
quiz1            	exercises/quiz1.rs                            	Done
move_semantics1  	exercises/move_semantics/move_semantics1.rs   	Done
move_semantics2  	exercises/move_semantics/move_semantics2.rs   	Done
move_semantics3  	exercises/move_semantics/move_semantics3.rs   	Done
move_semantics4  	exercises/move_semantics/move_semantics4.rs   	Done
move_semantics5  	exercises/move_semantics/move_semantics5.rs   	Done
move_semantics6  	exercises/move_semantics/move_semantics6.rs   	Done
primitive_types1 	exercises/primitive_types/primitive_types1.rs 	Done
primitive_types2 	exercises/primitive_types/primitive_types2.rs 	Done
primitive_types3 	exercises/primitive_types/primitive_types3.rs 	Done
primitive_types4 	exercises/primitive_types/primitive_types4.rs 	Done
primitive_types5 	exercises/primitive_types/primitive_types5.rs 	Done
primitive_types6 	exercises/primitive_types/primitive_types6.rs 	Done
structs1         	exercises/structs/structs1.rs                 	Done
structs2         	exercises/structs/structs2.rs                 	Done
structs3         	exercises/structs/structs3.rs                 	Done
enums1           	exercises/enums/enums1.rs                     	Done
enums2           	exercises/enums/enums2.rs                     	Done
enums3           	exercises/enums/enums3.rs                     	Done
modules1         	exercises/modules/modules1.rs                 	Done
modules2         	exercises/modules/modules2.rs                 	Done
modules3         	exercises/modules/modules3.rs                 	Done
vec1             	exercises/collections/vec1.rs                 	Done
vec2             	exercises/collections/vec2.rs                 	Done
hashmap1         	exercises/collections/hashmap1.rs             	Done
hashmap2         	exercises/collections/hashmap2.rs             	Done
strings1         	exercises/strings/strings1.rs                 	Done
strings2         	exercises/strings/strings2.rs                 	Done
quiz2            	exercises/quiz2.rs                            	Done
errors1          	exercises/error_handling/errors1.rs           	Done
errors2          	exercises/error_handling/errors2.rs           	Done
errors3          	exercises/error_handling/errors3.rs           	Done
errors4          	exercises/error_handling/errors4.rs           	Done
errors5          	exercises/error_handling/errors5.rs           	Done
errors6          	exercises/error_handling/errors6.rs           	Done
generics1        	exercises/generics/generics1.rs               	Done
generics2        	exercises/generics/generics2.rs               	Done
generics3        	exercises/generics/generics3.rs               	Done
option1          	exercises/option/option1.rs                   	Done
option2          	exercises/option/option2.rs                   	Done
option3          	exercises/option/option3.rs                   	Done
traits1          	exercises/traits/traits1.rs                   	Done
traits2          	exercises/traits/traits2.rs                   	Done
tests1           	exercises/tests/tests1.rs                     	Done
tests2           	exercises/tests/tests2.rs                     	Done
tests3           	exercises/tests/tests3.rs                     	Done
quiz3            	exercises/quiz3.rs                            	Done
box1             	exercises/standard_library_types/box1.rs      	Done
arc1             	exercises/standard_library_types/arc1.rs      	Done
iterators1       	exercises/standard_library_types/iterators1.rs	Done
iterators2       	exercises/standard_library_types/iterators2.rs	Done
iterators3       	exercises/standard_library_types/iterators3.rs	Done
iterators4       	exercises/standard_library_types/iterators4.rs	Done
iterators5       	exercises/standard_library_types/iterators5.rs	Done
threads1         	exercises/threads/threads1.rs                 	Done
macros1          	exercises/macros/macros1.rs                   	Pending
macros2          	exercises/macros/macros2.rs                   	Pending
macros3          	exercises/macros/macros3.rs                   	Pending
macros4          	exercises/macros/macros4.rs                   	Pending
quiz4            	exercises/quiz4.rs                            	Done
clippy1          	exercises/clippy/clippy1.rs                   	Done
clippy2          	exercises/clippy/clippy2.rs                   	Done
using_as         	exercises/conversions/using_as.rs             	Done
from_into        	exercises/conversions/from_into.rs            	Done
from_str         	exercises/conversions/from_str.rs             	Done
try_from_into    	exercises/conversions/try_from_into.rs        	Done
as_ref_mut       	exercises/conversions/as_ref_mut.rs           	Done
advanced_errs1   	exercises/advanced_errors/advanced_errs1.rs   	Pending
advanced_errs2   	exercises/advanced_errors/advanced_errs2.rs   	Pending
Progress: You completed 78 / 84 exercises (92.86 %).
```

Greetings and welcome to `rustlings`. This project contains small exercises to get you used to reading and writing Rust code. This includes reading and responding to compiler messages!

_...looking for the old, web-based version of Rustlings? Try [here](https://github.com/rust-lang/rustlings/tree/rustlings-1)_

Alternatively, for a first-time Rust learner, there are several other resources:

- [The Book](https://doc.rust-lang.org/book/index.html) - The most comprehensive resource for learning Rust, but a bit theoretical sometimes. You will be using this along with Rustlings!
- [Rust By Example](https://doc.rust-lang.org/rust-by-example/index.html) - Learn Rust by solving little exercises! It's almost like `rustlings`, but online

## Getting Started

_Note: If you're on MacOS, make sure you've installed Xcode and its developer tools by typing `xcode-select --install`._
_Note: If you're on Linux, make sure you've installed gcc. Deb: `sudo apt install gcc`. Yum: `sudo yum -y install gcc`._

You will need to have Rust installed. You can get it by visiting https://rustup.rs. This'll also install Cargo, Rust's package/project manager.

## MacOS/Linux

Just run:

```bash
curl -L https://git.io/install-rustlings | bash
# Or if you want it to be installed to a different path:
curl -L https://git.io/install-rustlings | bash -s mypath/
```

This will install Rustlings and give you access to the `rustlings` command. Run it to get started!

## Windows

In PowerShell (Run as Administrator), set `ExecutionPolicy` to `RemoteSigned`:

```ps1
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

Then, you can run:

```ps1
Start-BitsTransfer -Source https://git.io/JTL5v -Destination $env:TMP/install_rustlings.ps1; Unblock-File $env:TMP/install_rustlings.ps1; Invoke-Expression $env:TMP/install_rustlings.ps1
```

To install Rustlings. Same as on MacOS/Linux, you will have access to the `rustlings` command after it.

When you get a permission denied message then you have to exclude the directory where you placed the rustlings in your virus-scanner

## Browser:

[Run on Repl.it](https://repl.it/github/rust-lang/rustlings)

[Open in Gitpod](https://gitpod.io/#https://github.com/rust-lang/rustlings)

## Manually

Basically: Clone the repository at the latest tag, run `cargo install`.

```bash
# find out the latest version at https://github.com/rust-lang/rustlings/releases/latest (on edit 4.6.0)
git clone -b 4.6.0 --depth 1 https://github.com/rust-lang/rustlings
cd rustlings
cargo install --force --path .
```

If there are installation errors, ensure that your toolchain is up to date. For the latest, run:

```bash
rustup update
```

Then, same as above, run `rustlings` to get started.

## Doing exercises

The exercises are sorted by topic and can be found in the subdirectory `rustlings/exercises/<topic>`. For every topic there is an additional README file with some resources to get you started on the topic. We really recommend that you have a look at them before you start.

The task is simple. Most exercises contain an error that keeps them from compiling, and it's up to you to fix it! Some exercises are also run as tests, but rustlings handles them all the same. To run the exercises in the recommended order, execute:

```bash
rustlings watch
```

This will try to verify the completion of every exercise in a predetermined order (what we think is best for newcomers). It will also rerun automatically every time you change a file in the `exercises/` directory. If you want to only run it once, you can use:

```bash
rustlings verify
```

This will do the same as watch, but it'll quit after running.

In case you want to go by your own order, or want to only verify a single exercise, you can run:

```bash
rustlings run myExercise1
```

Or simply use the following command to run the next unsolved exercise in the course:

```bash
rustlings run next
```

In case you get stuck, you can run the following command to get a hint for your
exercise:

```bash
rustlings hint myExercise1
```

You can also get the hint for the next unsolved exercise with the following command:

```bash
rustlings hint next
```

To check your progress, you can run the following command:

```bash
rustlings list
```

## Testing yourself

After every couple of sections, there will be a quiz that'll test your knowledge on a bunch of sections at once. These quizzes are found in `exercises/quizN.rs`.

## Enabling `rust-analyzer`

`rust-analyzer` support is provided, but it depends on your editor
whether it's enabled by default. (RLS support is not provided)

To enable `rust-analyzer`, you'll need to make Cargo build the project
with the `exercises` feature, which will automatically include the `exercises/`
subfolder in the project. The easiest way to do this is to tell your editor to
build the project with all features (the equivalent of `cargo build --all-features`).
For specific editor instructions:

- **VSCode**: Add a `.vscode/settings.json` file with the following:

```json
{
  "rust-analyzer.cargo.features": ["exercises"]
}
```

- **IntelliJ-based Editors**: Using the Rust plugin, everything should work
  by default.
- _Missing your editor? Feel free to contribute more instructions!_

## Continuing On

Once you've completed Rustlings, put your new knowledge to good use! Continue practicing your Rust skills by building your own projects, contributing to Rustlings, or finding other open-source projects to contribute to.

## Uninstalling Rustlings

If you want to remove Rustlings from your system, there's two steps. First, you'll need to remove the exercises folder that the install script created
for you:

```bash
rm -rf rustlings # or your custom folder name, if you chose and or renamed it
```

Second, since Rustlings got installed via `cargo install`, it's only reasonable to assume that you can also remove it using Cargo, and
exactly that is the case. Run `cargo uninstall` to remove the `rustlings` binary:

```bash
cargo uninstall rustlings
```

Now you should be done!

## Completion

Rustlings isn't done; there are a couple of sections that are very experimental and don't have proper documentation. These include:

- Errors (`exercises/errors/`)
- Option (`exercises/option/`)
- Result (`exercises/result/`)
- Move Semantics (could still be improved, `exercises/move_semantics/`)

Additionally, we could use exercises on a couple of topics:

- Structs
- Better ownership stuff
- `impl`
- ??? probably more

If you are interested in improving or adding new ones, please feel free to contribute! Read on for more information :)

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md).

## Contributors ✨

Thanks goes to the wonderful people listed in [AUTHORS.md](./AUTHORS.md) 🎉
