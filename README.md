# Waddle

## About

**Waddle** is a community-driven operating system that can be used for servers, everyday use, work, development, drawing, music production, etc.

>The operating system is still in development and is not stable. Do not use it for anything other than testing or development.

## Supported platforms

### Platforms that will be supported soon

* UEFI x86_64

## TODO

- [ ] Bootloader
- [ ] Kernel

This list may change over time.

## Build

### Requirements

* Git
* GCC
* CMake
* NASM
* QEMU
* Ninja

### Clone the repository

```
git clone https://github.com/jouderexe/waddle.git
```

### Configure

```
cmake -S . -B build
```

### Compilation
```
cmake --build build
```
### Run

> Running Waddle is not implemented yet.

## License

This project uses the **BSD 2-Clause License**.

See [`LICENSE`](LICENSE) for more information.

## Contributing

Contributions are welcome.

See [`docs/CONTRIBUTING.md`](docs/CONTRIBUTING.md) for more information.

## Documentation

Documentation is available in the [`docs/`](docs/) directory.

Useful resources for OS development include:

* [Intel® 64 and IA-32 Architectures Software Developer Manuals](https://www.intel.com/content/www/us/en/developer/articles/technical/intel-sdm.html)
* [AMD Documentation Hub](https://www.amd.com/en/support/tech-docs)
* [UEFI Specification](https://uefi.org/specifications)

---

Created by jouderexe.