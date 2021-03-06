---
layout: default
title: Sponsor work on Rust!
---

# aturon's Rust sponsorship list

| Patreon | GitHub | Interests |
|---------|--------|-----------|
| [Leonardo Yvens](https://www.patreon.com/leodasvacas) | [@leodasvacas](https://github.com/leodasvacas/) | [rustc (trait system), community work](#leonardo-yvens-leodasvacas) |
| [Aleksey Kladov](https://www.patreon.com/matklad) | [@matklad](https://github.com/matklad) | [IDEs, Cargo, rustc](#aleksey-kladov-matklad) |
| [Grey Mitchell](https://www.patreon.com/QuietMisdreavus) | [@QuietMisdreavus](https://github.com/QuietMisdreavus) | [rustdoc, documentation](#grey-mitchell-quietmisdreavus) |
| [Igor Matuszewski](https://www.patreon.com/xanewok) | [@Xanewok](https://github.com/xanewok) | [RLS and other dev tools](#igor-matuszewski-xanewok) |
| [Stjepan Glavina](https://www.patreon.com/stjepang) | [@stjepang](https://github.com/stjepang) | [crossbeam, all things Rust concurrency](#stjepan-glavina-stjepang) |
| [Jorge Aparicio](https://www.patreon.com/japaric/) | [@japaric](https://github.com/japaric) | [Rust on embedded devices](#jorge-aparicio-japaric) |
| [Chris Krycho](https://www.patreon.com/newrustacean/) | [@chriskrycho](https://github.com/chriskrycho) | [New Rustacean podcast](#chris-krycho-chriskrycho) |
| [Matthias Endler](https://www.patreon.com/hellorust/) | [@mre](https://github.com/mre) | [Hello Rust! live-coding show](#matthias-endler-mre) |
| [Peter Atashian](https://www.patreon.com/retep998) | [@retep998](https://github.com/retep998) | [winapi](https://github.com/retep998/winapi-rs) |
| [Pierre Krieger](https://www.patreon.com/tomaka) | [@tomaka](https://github.com/tomaka) | [graphics APIs, audio APIs, Android packaging](#pierre-krieger-tomaka) |
| [Florian Gilcher](https://yakshav.es/sponsor-florian) | [@skade](https://github.com/skade) | [RustFest conferences, Community team, Events team lead](https://blog.rustfest.eu/past_events/) |

Rust and its ecosystem is developed by a diverse mix of staff (from a variety of
companies) and volunteers, from all over the world and with a range of
circumstances. And "developed" goes far beyond code, to include documentation,
podcasts, community work, and more.

People and companies often ask how they can give back to the community and
sponsor important work in the Rust world. **I think the best approach is to
provide direct "match-making" between sponsors and people doing valuable work**,
making it possible for sponsors to direct their funds and making the individuals
more visible.

This page is a first attempt at facilitating sponsorship. **This is not an
officially endorsed list**, but it is a list of Rustaceans that I have
personally vetted and sponsored, and encourage you to support. Each of them has
a long, public history of impactful work in the community.

Use the Patreon links to sponsor individuals, contact them directly for contract
work, or write me at aturon@mozilla.com to find another arrangement.

If you're interested in being vetted for this list, please reach out.

---

# Leonardo Yvens (@leodasvacas)

## Interests: rustc (trait system), community work

- [Patreon](https://www.patreon.com/leodasvacas)
- [GitHub](https://github.com/leodasvacas/), [email](mailto:leoyvens@gmail.com)
- Open to direct contract work

### Details

- **Chalk:** I’m up for just about anything anything involving rustc, though something related to type checking and chalk ****might be the best use of my previous experience.
- **Coercions**: I’m particularly interested in the interaction between **[coercions and type checking](https://github.com/rust-lang-nursery/chalk/issues/104)**. The holy grail here would be to have type checking be smarter around method calls and better transitive coercions. This would be implemented by leveraging chalk.
- **Type parameter defaults**: I have an interest in the stalled [**type parameter defaults** feature](https://github.com/rust-lang/rust/issues/27336) and would like to work on a new RFC and implementation for it’s interaction with inference.
- **Community work**: Giving more talks and workshops and helping the Brazilian and Latin America community organize more Rust events.

---

# Aleksey Kladov (@matklad)

## Interests: IDEs, Cargo, rustc

- [Patreon](https://www.patreon.com/matklad)
- [GitHub](https://github.com/matklad), [email](mailto:aleksey.kladov@gmail.com)
- Open to direct contract work

### Details

- **RLS**: as an original developer of the [Rust plugin](http://github.com/intellij-rust/intellij-rust) for JetBrains IDEs, I have a deep understanding of challenges and specifics of a good IDE backend. While I believe that writing a Rust compiler frontend from scratch in Kotlin was the best choice for IntelliJ, it is also important that the official Rust toolchain has all important IDE features as well. I've made a [few contributions](https://github.com/rust-lang-nursery/rls/commits?author=matklad) to RLS so far, because I was busy with IntelliJ Rust, but now I want to transfer more of my experience to this project.
- Making `rustc` a better fit for IDEs: there are [big differences](https://www.reddit.com/r/rust/comments/5rhqj0/) in how command line compiler and IDE should process code for the best user experience. Incremental on-demand compilation is a great step towards making `rustc` more suited for IDEs, but there are more things that should be done. In particular, I would like to lay a solid foundation for IDEs by starting from the lowest level -- lexer and parser. The plan is outlined in the [libsyntax2 RFC](https://github.com/rust-lang/rfcs/pull/2256).
- **Cargo**: I've working on Cargo for a long time. Apart from the usual maintenance work, I am especially interested in integration with IDEs and build systems.

---

# Grey Mitchell (@QuietMisdreavus)

## Interests: rustdoc, documentation

- [Patreon](https://www.patreon.com/QuietMisdreavus)
- [GitHub](https://github.com/QuietMisdreavus), [email](mailto:grey@quietmisdreavus.net)

### Details

- **Rustdoc**. As the current lead of the Rustdoc Team, I help organize contributions to the official documentation tool of Rust. I’ve made multiple contributions to various areas of rustdoc, from the appearance of code on the final page to the base of how it collects data from the compiler.
- **Documentation**. In my own crates and in my work on rustdoc, I’ve always wanted to improve the state of documentation in the Rust community. I’ve written guides to using a crate, to using specific rustdoc features, and to the internals of rustdoc itself. With access to information about the use of a feature or library, I can help extend and improve its docs.

---

# Igor Matuszewski (@Xanewok)

## Interests: RLS and other dev tools

- [Patreon](https://www.patreon.com/xanewok)
- [GitHub](https://github.com/xanewok), [email](mailto:xanewok@gmail.com)
- Open to direct contract work

### Details

- **RLS**. As a member of Rust IDEs and editors team, I mostly hack on the RLS, the core Rust IDE tool. In addition to helping maintain the project, my work mostly revolved around supporting Cargo workspaces in the RLS and bringing other quality-of-life improvements. However, there's still much to do, most importantly implementing compiler-suggested code completion, improving macro support or integration with other build systems.
- **Tooling.** In addition to RLS itself, I also worked on few tooling-related features when working on the RLS. It mostly consisted of improving interop between RLS and other tools, including the Rust compiler. I'd like to continue working on other tooling-related issues, such as improving the build plan integration in Cargo and RLS or helping with the planned rustup/Cargo refactor.

---

# Stjepan Glavina (@stjepang)

## Interests: crossbeam, all things Rust concurrency

- [Patreon](https://www.patreon.com/stjepang)
- [GitHub](https://github.com/stjepang), [email](mailto:stjepang@gmail.com)
- Open to direct contract work

### Details

- **Epoch-based GC**. This garbage collection mechanism in Crossbeam works quite well already, but its performance can still be improved. The interface is at the moment not very easy to use and could use additional design work.
- **Hazard pointers.** This is another popular garbage collection mechanism with different tradeoffs. It’s generally a better choice for working with concurrently modified single objects, while epoch-based GC is faster for traversing graphs of objects. Hazard pointers are an important prerequisite for implementing a primitive similar to [AtomicReference](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/atomic/AtomicReference.html) in Rust.
- **Atomic primitives**. Building a set of atomic primitives in Rust. We do have std::sync::atomic, but it’s somewhat basic and unergonomic. I’m interested in creating AtomicBox and AtomicArc, which would be akin to [std::atomic_shared_ptr](http://en.cppreference.com/w/cpp/experimental/atomic_shared_ptr) in C++ o[r AtomicReference](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/atomic/AtomicReference.html) in Java. Another new primitive might be scalable counters like [LongAdder](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/atomic/LongAdder.html) in Java.
- **Channels and queues**. Working on crossbeam-channel has given me the idea to create a coherent set of concurrent queues with different kinds of tradeoffs. In Java, those would be [ArrayBlockingQueue](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ArrayBlockingQueue.html), [ConcurrentLinkedQueue](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ConcurrentLinkedQueue.html), [LinkedBlockingQueue](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/LinkedBlockingQueue.html), and several others.
- **Improving parallel sorts**. In Rayon, par_sort_unstable uses a parallel pattern-defeating quicksort, but it doesn’t scale as well as it could because the partitioning phase is still sequential. [IPS4O](https://github.com/SaschaWitt/ips4o) is a state-of-the-art parallel in-place sorting algorithm and would be the perfect fit here.
- **Concurrent data structures**. I’m interested in building these kinds of data structures in general. This is still a largely unexplored area of research and engineering, and I believe Rust has unique properties (ownership system, data race freedom, doesn’t rely on GC) that could push this area forward.

---

# Jorge Aparicio (@japaric)

## Interests: Rust on embedded devices

- [Patreon](https://www.patreon.com/japaric/)
- [GitHub](https://github.com/japaric), [email](mailto:jorge@japaric.io)

### Details

I want Rust to become a major player in the field of embedded systems as I believe it holds so much potential to improve the status quo. To that effect, I have been doing a bunch of groundwork in this area. Here's some of my recent work:

- Lead of the [embedded devices WG](https://github.com/rust-lang-nursery/embedded-wg). This WG is an official part of the Rust project and we are working towards making embedded Rust a first class citizen. Check our [goals for the 2018 edition](https://github.com/rust-lang-nursery/embedded-wg/issues?q=is%3Aopen+is%3Aissue+milestone%3A%222018+edition%22).
- [Embedded Rust on stable](https://github.com/rust-lang-nursery/embedded-wg/issues/42)
- [Xargo](https://github.com/japaric/xargo), a Cargo wrapper for `no-std` development. Used for embedded, OS and game development! Notable users: [Baidu](https://github.com/baidu/rust-sgx-sdk), [Chucklefish](https://www.reddit.com/r/rust/comments/78bowa/hey_this_is_kyren_from_chucklefish_we_make_and/) and [Redox OS](https://www.redox-os.org/).
- [Cross](https://github.com/japaric/cross#cross), a Cargo wrapper that eases cross compiling Rust programs to tons of different architectures (ARM, MIPS, PowerPC, System Z, etc.). Used by Microsoft in their [Azure IoT Edge project](https://github.com/Azure/iotedge/tree/master/edgelet) build system.
- [`svd2rust`](https://docs.rs/svd2rust), a Rust code generator that produces an API to access a device's peripherals from SVD files.
- A bunch of `no_std` crates: [`cortex-m`](https://docs.rs/cortex-m) for access to common Cortex-M functionality, device crates like the [`stm32f30x`](https://docs.rs/stm32f30x), Board Support Package (BSP) crates like the [`f3`](https://docs.rs/f3) and miscellaneous `no-std` crates like [`fpa`](https://docs.rs/fpa) for fast Fixed Point Arithmetic.
- [Compiler hacking](https://github.com/rust-lang/rust/pulls?q=is%3Apr+author%3Ajaparic+is%3Aclosed): [`-Z linker-flavor`](https://github.com/rust-lang/rust/pull/40018), [`#[used]`](https://github.com/rust-lang/rust/pull/39987), [MSP430 support](https://github.com/rust-lang/rust/pull/37672), [llvm-tools component](https://github.com/rust-lang/rust/pull/50336), etc.
- [The Discovery book](https://japaric.github.io/discovery/), a beginner friendly text about programming microcontrollers in Rust. And,
- [The Real Time for The Masses framework](https://docs.rs/cortex-m-rtfm/) for embedded concurrent programming.

But there's still lots of ecosystem and tooling work to do! Among my ongoing work you'll find:

- Pushing embedded Rust on stable [over the finish line](https://github.com/rust-lang/rust/pull/51366).
- Embedded Rust documentation: writing the [embedded Rust book](https://github.com/rust-lang-nursery/embedded-wg/issues/56), finishing the [embedonomicon](https://github.com/rust-lang-nursery/embedded-wg/issues/59), updating the [Discovery](https://japaric.github.io/discovery/) book
- Expanding the members of the rust-embedded org to have more people maintain the embedded Rust / Cortex-M ecosystem
- Making the Real Time for The Masses framework work in a future stable release

---

# Chris Krycho (@chriskrycho)

## Interests: New Rustacean podcast

- [Patreon](https://www.patreon.com/newrustacean/)
- [GitHub](https://github.com/chriskrycho), [email](mailto:chris@chriskrycho.com)

### Details

[A show](https://newrustacean.com/) by @chriskrycho about learning
@RustLang. Technical—but approachable!  Topical deep dives, interviews, crate
overviews, and more.

---

# Matthias Endler (@mre)

## Interests: Hello Rust! live-coding show

- [Patreon](https://www.patreon.com/hellorust/)
- [GitHub](https://github.com/mre)

### Details

[A live-coding show](https://hello-rust.show/) about Rust, targeted towards
intermediate Rust programmers who have already read the Rust book and want to learn
advanced patterns and tricks as well as how to write ergonomic code in Rust.

---

# Peter Atashian (@retep998)

## Interests: winapi

- [Patreon](https://www.patreon.com/retep998)
- [GitHub](https://github.com/retep998)
- Open to direct contract work

### Details

The [winapi crate](https://github.com/retep998/winapi-rs) provides raw FFI
bindings to all of Windows API. They are gathered by hand using the Windows 10
SDK from Microsoft

---

# Pierre Krieger (@tomaka)

## Interests: graphics APIs, audio APIs, Android packaging

- [Patreon](https://www.patreon.com/tomaka)
- [GitHub](https://github.com/tomaka), [email](mailto:pierre.krieger1708@gmail.com)

### Details

- [Vulkano](http://vulkano.rs/) (~45k lines of code) is a safe wrapper around the Vulkan API. It is a low-level brick that allows you to interact with your GPU and execute graphical or compute (GPGPU) operations. Vulkano aims to be very explicit and predictable especially if you are familiar with the Vulkan API, but at the same time provide some high-level functionnalities. Ideal for building a game, a game engine, or a GPGPU application when performances and explicitness matter.

- [Glium](https://github.com/glium/glium) (~33k lines of code, unmaintained) is a safe wrapper around OpenGL and OpenGL ES. It aims to provide an easy-to-use high-level API while still remaining predictable and not hiding what it does. Even though many people have liked glium, its main goal of being safe was determined to be too difficult because of the many problems with OpenGL itself.

- [Android-rs-glue](https://github.com/tomaka/android-rs-glue) allows you to easily turn your Rust code into an Android package. After installing the Android SDK and NDK, run the `cargo apk` command and you will get an .apk file which you can then install on your device. Works out of the box with vulkano, glium, winit and glutin. Also provides a docker image.

- [Winit](https://github.com/tomaka/winit) (~10k lines of code) is a cross-platform window creation library. It allows you to create a basic window on Windows, Linux, MacOS and Android, then lets you handle the events received by this window. In order to show something on the window, you are supposed to create an OpenGL, Vulkan, or DirectX context on top of it, but this is not covered by winit itself.

- [Glutin](https://github.com/tomaka/glutin) (~7k lines of code) does the same as winit, but creates an OpenGL context in a cross-platform way on top of the window. The servo project from Mozilla uses a fork of glutin for its own windowing.

(more projects detailed in the [Patreon page](https://www.patreon.com/tomaka))
