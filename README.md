[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FElectricRCAircraftGuy%2FeRCaGuy_hello_world&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=views+%28today+%2F+total%29&edge_flat=false)](https://hits.seeyoufarm.com)

[>> Sponsor Me on GitHub <<](https://github.com/sponsors/ElectricRCAircraftGuy)


# eRCaGuy_hello_world
"hello world" demos &amp; templates for various languages, incl. `gcc` build commands for C &amp; C++ 

See also my [eRCaGuy_hello_world_data](https://github.com/ElectricRCAircraftGuy/eRCaGuy_hello_world_data) project. 

By Gabriel Staples  
www.ElectricRCAircraftGuy.com  

- Disclaimer: any content herein is my own or otherwise has proper notice of licensing and attribution. This repo contains my own beliefs, opinions, words and works. They are _not_ endorsed by any of my past nor present employers.


## Other, very-useful repos:
1. My [eRCaGuy_dotfiles](https://github.com/ElectricRCAircraftGuy/eRCaGuy_dotfiles) repo.


## Popular online interactive tools & resources
1. Free:
    1. https://www.onlinegdb.com/ - compile, run, save, share, and debug with `gdb`, your code online
    1. https://godbolt.org/ - Compiler Explorer: view the compiled assembler output of your code
    1. \*\*\*\*\* [My favorite for C++!] https://cppinsights.io/ - a tool for understanding and expanding cryptic C++ so that it goes from implicit to explicit! See how `auto` expands, what explicit types implicit types are, how range-based `for` loop expand, how arrays, structs, classes, etc., are initialized, etc.
        1. My answer here references it: [Coderpad's new C++ example is cryptic: meaning of `auto` and `const char* const&`](https://stackoverflow.com/a/75656629/4561887)
    1. https://cdecl.org/ - convert C and C++ pointers and complex types to plain English
    1. https://regex101.com/ - expand, test, and understand regular expressions
    1. https://asciiflow.com/#/ - draw ASCII diagrams and documentation, for text-based readmes, online.
1. Paid:
    1. https://coderpad.io/ - for sharing code when giving or taking online interviews; practice in the sandbox before an interview here: https://app.coderpad.io/sandbox
    1. https://www.lucidchart.com/pages/ - a popular diagramming tool used by many top tech companies


## Also very useful:
1. **Learn X in Y minutes**: for _most-excellent_ software tutorials written in code in the language itself which you are learning!
    1. Main Website: https://learnxinyminutes.com/
    1. GitHub: https://github.com/adambard/learnxinyminutes-docs
    1. Example tutorials:
        1. Ones I'd like to study next are marked with a star: ⭐. Ones I have fully studied are marked with a check (none so far): ✅.
        1. Languages:
            1. C - https://learnxinyminutes.com/docs/c/
            1. C++ - https://learnxinyminutes.com/docs/c++/
            1. Python - https://learnxinyminutes.com/docs/python/
            1. Go - https://learnxinyminutes.com/docs/go/
        1. Tools [I know I know!...I consider some of these programming languages too!--like `bash` and `awk`]:
            1. Bash - https://learnxinyminutes.com/docs/bash/
            1. awk - https://learnxinyminutes.com/docs/awk/
            1. cmake⭐ - https://learnxinyminutes.com/docs/cmake/
            1. ansible - https://learnxinyminutes.com/docs/ansible/
            1. git - https://learnxinyminutes.com/docs/git/
            1. make⭐ - https://learnxinyminutes.com/docs/make/
            1. linker scripts (Russian only--use Google Translate) - https://learnxinyminutes.com/docs/linker/
            1. vim - https://learnxinyminutes.com/docs/vim/
1. https://www.learncpp.com/
1. LOOKS VERY USEFUL: https://makefiletutorial.com/


## Some other pages
1. [NOTES_architecture_and_best_practices.md](NOTES_architecture_and_best_practices.md) - some of my notes on software architecture and best practices, including when using microcontrollers and FreeRTOS.
1. [low_level.md: What does "low level" mean? Do you want that? It depends.](low_level.md)
1. [c/README.md](c/README.md)
1. [cpp/README.md](cpp/README.md)
1. [python/README.md](python/README.md)
    1. [python/pandas_README.md](python/pandas_README.md)


# Table of Contents
<details>
<summary><b>(click to expand)</b></summary>
<!-- MarkdownTOC -->

1. [Status:](#status)
1. [Description: _for beginners and experts alike!_--not your average "hello world" examples](#description-_for-beginners-and-experts-alike_--not-your-average-hello-world-examples)
1. [How to clone this repo and all git submodules and git lfs files \(including tracked binary files, such as PDFs\)](#how-to-clone-this-repo-and-all-git-submodules-and-git-lfs-files-including-tracked-binary-files-such-as-pdfs)
        1. [To clone this repo plus all sub-repos \(git submodules\) and all `git lfs` Large File Storage files](#to-clone-this-repo-plus-all-sub-repos-git-submodules-and-all-git-lfs-large-file-storage-files)
        1. [To update this repo as a _user_ of it, to match it exactly as I have made it as the developer of it](#to-update-this-repo-as-a-user-of-it-to-match-it-exactly-as-i-have-made-it-as-the-developer-of-it)
1. [A Few Folder & File Notes](#a-few-folder--file-notes)
1. [Examples of more advanced principles taught herein:](#examples-of-more-advanced-principles-taught-herein)
    1. [1. C and C++:](#1-c-and-c)
            1. [Online community wiki reference pages](#online-community-wiki-reference-pages)
            1. [Code examples:](#code-examples)
        1. [Additional C and C++ build notes \(ex: w/`gcc` or `clang` compilers\):](#additional-c-and-c-build-notes-ex-wgcc-or-clang-compilers)
    1. [2. Python:](#2-python)
    1. [3. markdown:](#3-markdown)
    1. [4. bash:](#4-bash)
    1. [5. awk:](#5-awk)
    1. [6. Arduino:](#6-arduino)
1. [Useful tips and tricks:](#useful-tips-and-tricks)
    1. [Running a C file as an executable Bash script](#running-a-c-file-as-an-executable-bash-script)
1. [File Structure:](#file-structure)
1. [Changelog](#changelog)
    1. [\[v0.3.0\] - 2020-05-23](#v030---2020-05-23)
    1. [\[v0.2.0\] - 2020-04-18](#v020---2020-04-18)
    1. [\[v0.1.0\] - 2020-04-14](#v010---2020-04-14)

<!-- /MarkdownTOC -->
</details>


<a id="status"></a>
# Status:
1. Many solid C & C++ demos are done and work! 
1. A Python demo also is in place to show how to parse a YAML file. 
1. [bash/argument_parsing__3_advanced__gen_prog_template.sh](bash/argument_parsing__3_advanced__gen_prog_template.sh) is a _really good_ advanced bash demo of a full program with advanced features, help menu, full argument parsing, etc. See the [bash](#4-bash) section below.

See the `tree` output below to see the file/folder structure.


<a id="description-_for-beginners-and-experts-alike_--not-your-average-hello-world-examples"></a>
# Description: _for beginners and experts alike!_--not your average "hello world" examples

Note that these are NOT just your standard "simple" hello world demos for absolute beginners. Rather, they are simple enough for beginners but also contain some advanced techniques and tips & tricks to act as good reminders or teaching for more expert programmers too. I, myself, regularly reference my own examples here to remind myself of some of these details which are easy to forget. There's no sense stressing about trying to remember everything. _Instead of trying to remember everything, just remember where to look (here in this case)_. 


<a id="how-to-clone-whole-repo"></a>
<a id="how-to-clone-this-repo-and-all-git-submodules-and-git-lfs-files-including-tracked-binary-files-such-as-pdfs"></a>
# How to clone this repo and all git submodules and git lfs files (including tracked binary files, such as PDFs)

This repo contains [Git Submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules), which simply means that this is a git repo which contains other git repos. It also uses [`git lfs` (Large File Storage)](https://git-lfs.com/) to more-efficiently store certain binary files, such as PDFs. 

- **For details on how to use `git submodule` and `git lfs`, see my notes in my [eRCaGuy_dotfiles](https://github.com/ElectricRCAircraftGuy/eRCaGuy_dotfiles) repo here: [how-to-clone-whole-repo](https://github.com/ElectricRCAircraftGuy/eRCaGuy_dotfiles#how-to-clone-whole-repo).** 
- See also the `= git submodules: =` section of my "git & Linux cmds doc" notes in my [eRCaGuy_dotfiles](https://github.com/ElectricRCAircraftGuy/eRCaGuy_dotfiles) repo here: [eRCaGuy_dotfiles/git & Linux cmds, help, tips & tricks - Gabriel.txt](https://github.com/ElectricRCAircraftGuy/eRCaGuy_dotfiles/blob/master/git%20%26%20Linux%20cmds%2C%20help%2C%20tips%20%26%20tricks%20-%20Gabriel.txt).

In short:

<a id="to-clone-this-repo-plus-all-sub-repos-git-submodules-and-all-git-lfs-large-file-storage-files"></a>
### To clone this repo plus all sub-repos (git submodules) and all `git lfs` Large File Storage files

```bash
# Clone this repo
git clone https://github.com/ElectricRCAircraftGuy/eRCaGuy_hello_world.git
# Pull all Git LFS files (large binary files, such as PDFs, tracked with `git lfs`)
git lfs pull
# Recursively clone and update all subrepos (git submodules) it may contain
git submodule update --init --recursive
```

<a id="to-update-this-repo-as-a-user-of-it-to-match-it-exactly-as-i-have-made-it-as-the-developer-of-it"></a>
### To update this repo as a _user_ of it, to match it exactly as I have made it as the developer of it

```bash
git pull
git lfs pull
git submodule update --init --recursive
```


<a id="a-few-folder--file-notes"></a>
# A Few Folder & File Notes

1. Find some sample interview preparation code and notes by running `./find_interview_prep.sh`, which is located at the root of the repo. 
    
    Note: you can _be_ in _any_ directory when you run it, and it will always return the same answer, since it runs from its location, not from the location you are in when you call the executable. 

    Example run and output:
    ```bash
    eRCaGuy_hello_world$ ./find_interview_prep.sh 
    Finding all "interview prep" files in directory "/home/gabriel/GS/dev/eRCaGuy_hello_world" and lower.
    find_interview_prep.sh
    cpp/string_concatenate.cpp
    Done. 2 file(s) found.
    ```
1. You can add this as an **Eclipse project**--for source code navigation _only_, NOT for building! The Eclipse project files/folders are:
    1. `.cproject` file
    1. `.project` file
    1. `.settings` dir
1. `.clang-format` is the format definition file for auto-formatting C and C++ files with `clang-format`. 
    1. For full installation and usage instructions for `clang-format`, see the readme in my other repo here: https://github.com/ElectricRCAircraftGuy/eRCaGuy_CodeFormatter.
    1. Quick usage example: 
        ```bash
        # Format this file in-place (`-i`)
        clang-format --verbose -i --style=file "path/to/file.c"
        ```
    1. See the other repo here (https://github.com/ElectricRCAircraftGuy/eRCaGuy_CodeFormatter#usage) for more info on what `--style=file` means and how you can place the `.clang-format` configuration file at different levels.


<a id="examples-of-more-advanced-principles-taught-herein"></a>
# Examples of more advanced principles taught herein:


<a id="1-c-and-c"></a>
## 1. C and C++:


<a id="online-community-wiki-reference-pages"></a>
#### Online community wiki reference pages
1. https://en.cppreference.com/ - most popular; hard to understand; cryptic; pedantic; most-thorough and complete; written like it's for a programming language lawyer; covers up to C++17 and is working on C++20
1. https://cplusplus.com/reference/ - much easier to understand; better examples and explanations; written like it's for normal humans and programmers; but less complete and less-thorough; maybe only covers up to C++11


<a id="code-examples"></a>
#### Code examples:

1. How to generate intermediate build files, including .ii, .s, and .o.
    1. See ["cpp/hello_world.cpp"](cpp/hello_world.cpp)
1. How to make a single file compile in both C and C++ by using the `#ifdef __cplusplus` `extern "C" {` brace trick
    1. See ["c/hello_world.c"](c/hello_world.c)
    1. Note: there is also such a thing as `extern "C++"`. Search the GNU gcc documentation here for that search string: https://gcc.gnu.org/onlinedocs/gcc.pdf. Ex: the top of p489, under the paragraph titled "_Language-linkage module attachment_", mentions `(extern "C" or extern "C++")`.
1. How to use a forward declaration of `printf` rather than including `stdio.h` to make it link
    1. See ["c/hello_world.c"](c/hello_world.c)
1. How to do cross-platform sleep in Windows or Linux
    1. See ["c/hello_world_sleep.c"](c/hello_world_sleep.c)
1. A reminder to use `-Wall -Werror` for better code safety and quality
    1. See ["c/hello_world.c"](c/hello_world.c)
1. How to use `g3` for full debugging info
    1. See ["c/hello_world.c"](c/hello_world.c) and
    1. ["c/hello_world_sleep.c"](c/hello_world_sleep.c)
1. How to specify the C or C++ version you are compiling for, such as `c90`, `c99`, or `c11` (C 2011), or `c++98`, `c++03` (C++ 2003), or `c++11` (C++ 2011)
    1. See ["c/hello_world.c"](c/hello_world.c) and
    1. ["c/hello_world_sleep.c"](c/hello_world_sleep.c)
1. How to pass entire functions or curly-brace-scoped `{ }` code blocks, as though they were a single parameter, into a macro to be evaluated
    1. See ["cpp/macro_practice/advanced_macro_usage_pass_in_entire_func.cpp"](cpp/macro_practice/advanced_macro_usage_pass_in_entire_func.cpp)
1. How to do integer rounding UP, DOWN, and to NEAREST whole integer during division using 3 different techniques: 1) macros, 2) gcc/clang statement expressions, and 3) C++ function templates. This also is a great unit test example using simple hand-written unit tests.
    1. See ["c/rounding_integer_division/"](c/rounding_integer_division/) directory
    1. If you'd like to see how to use googletest (gtest) and googlemock (gmock) instead of writing custom unit tests, see my other project here instead: https://github.com/ElectricRCAircraftGuy/eRCaGuy_gtest_practice. It also acts as a good demo of how to get up and running quickly with Google's Bazel build system.
1. Witness that the C++ `std::unordered_map<T_key, T_value>` unordered map (hash table) class automatically implicitly creates a new key/value pair each time you attempt to read OR write to a value (or any members of a complex value, such as a `struct` or `class`) which belongs to a **non-existing key**! In other words, reading or writing any key/value which does NOT yet exists causes `std::unordered_map<>` to automatically, dynamically, generate it right on the spot for you to access it! This is confusing behavior at first, as it happens implicitly behind the scenes, so it needs to be understood. _Once understood, it is a powerful feature to use, but a one or two-line comment to exlain that you intend dynamic allocation to happen, above any lines in production code where you use this, would be wise._
    1. See ["cpp/unordered_map_practice/unordered_map_hash_table_implicit_key_construction_test.cpp"](cpp/unordered_map_practice/unordered_map_hash_table_implicit_key_construction_test.cpp)
1. Case-insensitive `strncmp()` function, with unit tests.
    1. See ["c/strncmpci.c"](c/strncmpci.c)
1. Example of how to manually write unit tests.
    1. See ["c/strncmpci.c"](c/strncmpci.c)
    1. Note: for Google Test (gtest/gmock) examples, including how to use the [Bazel](https://bazel.build/) build system, see my repo here instead: https://github.com/ElectricRCAircraftGuy/eRCaGuy_gtest_practice.
1. Example of how to use ANSI color codes (ex: red and green) in terminal output. 
    1. It is possible to colorize and stylize/format your text you print to `stdout` or `stderr`, in any programming language, by surrounding the text with special ANSI color codes. This works for _all programming languages_ and _all forms of printing_ to `stdout` or `stderr`, whether via `printf("some text\n");` in C or C++, `std::cout << "some text\n";` in C++, `print("some text")` in Python, `echo "some text"` in bash, etc.
    1. See these defines in C in ["c/strncmpci.c"](c/strncmpci.c):
        ```c
        #define ANSI_COLOR_OFF "\033[m"
        #define ANSI_COLOR_GRN "\033[32m"
        #define ANSI_COLOR_RED "\033[31m"
        ```
        ...and how I used them to colorize text in `printf()` calls there.
    1. See also my other repo here: https://github.com/ElectricRCAircraftGuy/eRCaGuy_dotfiles/blob/master/useful_scripts/git-diffn.sh#L126
1. How to use a `const` reference to a vector, with a default parameter, as an input param to a function!
    1. See ["cpp/onlinegdb--const_reference_to_vector__default_func_parameter.cpp"](cpp/onlinegdb--const_reference_to_vector__default_func_parameter.cpp)
1. How to call command-line system calls in C and C++, read piped input from `stdin`, and read command-line output from called process from its `stdout`:
    1. [c/system_call_list_files.c](c/system_call_list_files.c): basic example to call `ls -l` in C, but _not_ read back the output. Rather, it just prints to stdout instead. 
    1. See also:
        1. [StackOverflow.com: how to read from stdout in C](https://stackoverflow.com/q/24214038/4561887)
        1. [StackOverflow.com: C: Run a System Command and Get Output?](https://stackoverflow.com/q/646241/4561887)
        1. [StackOverflow.com: How can I run an external program from C and parse its output?](https://stackoverflow.com/q/43116/4561887)
        1. [StackOverflow.com: Capturing stdout from a system() command optimally](https://stackoverflow.com/q/125828/4561887)
        1. [the most-thorough C++ answer I think] [StackOverflow.com: How do I execute a command and get the output of the command within C++ using POSIX?](https://stackoverflow.com/q/478898/4561887)
1. Advanced bit-masks and bit-shifting. 
    1. See ["cpp/process_10_bit_video_data.cpp"](cpp/process_10_bit_video_data.cpp)
    1. See also the problem statement and my answer, with other references, on Stack Overflow here: [Stack Overflow: Add bit padding (bit shifting?) to 10bit values stored in a byte array](https://stackoverflow.com/a/66678338/4561887).
1. Weak functions (functions with attribute `weak`): prove to myself that weak functions which are declared but not defined really do have addresses equal to nil (ie: zero, or `0`), as this is how the Arduino `serialEvent()` function works and is implemented.
    1. See ["cpp/check_addr_of_weak_undefined_funcs.cpp"](cpp/check_addr_of_weak_undefined_funcs.cpp). 
    1. See also my Stack Overflow answer here: [Arduino “SerialEvent” example code doesn't work on my Arduino Nano. I can't receive serial data. Why?](https://stackoverflow.com/questions/67013619/arduino-serialevent-example-code-doesnt-work-on-my-arduino-nano-i-cant-rece/67016917#67016917).
    1. gcc `weak` function attribute: https://gcc.gnu.org/onlinedocs/gcc-3.2/gcc/Function-Attributes.html
        > weak
        > 
        > The `weak` attribute causes the declaration to be emitted as a weak symbol rather than a global. This is primarily useful in defining library functions which can be overridden in user code, though it can also be used with non-function declarations. Weak symbols are supported for ELF targets, and also for a.out targets when using the GNU assembler and linker.
1. Empirically measure the max _thread stack size_ permitted on your architecture, in C OR C++. See:
    1. My answer on Stack Overflow here: [Stack Overflow: C/C++ maximum stack size of program](https://stackoverflow.com/a/64085509/4561887)
    1. [c/onlinegdb--empirically_determine_max_thread_stack_size.md](c/onlinegdb--empirically_determine_max_thread_stack_size.md)
    1. [c/onlinegdb--empirically_determine_max_thread_stack_size_Bruno_Haible.c](c/onlinegdb--empirically_determine_max_thread_stack_size_Bruno_Haible.c)
    1. [c/onlinegdb--empirically_determine_max_thread_stack_size_GS_version.c](c/onlinegdb--empirically_