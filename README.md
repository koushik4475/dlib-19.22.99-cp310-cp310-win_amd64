# dlib 19.22.99 Wheel for Python 3.10 on Windows 64-bit (AMD64)

This repository provides the prebuilt `dlib-19.22.99-cp310-cp310-win_amd64.whl` Python package for **CPython 3.10 on 64-bit Windows (AMD64)**. It is intended for developers who need to install this specific dlib build without compiling the library locally.

## Compatibility

- Python implementation: CPython
- Python version: 3.10 (`cp310`)
- Operating system: Windows
- Architecture: 64-bit x86 (`win_amd64`)
- Package version: dlib 19.22.99

This wheel is not intended for Python 3.11+, 32-bit Windows, macOS, or Linux. Choose a wheel that matches your exact Python ABI and platform.

## Install

Download the wheel from this repository, open a terminal in the download directory, and run:

```bash
python -m pip install ./dlib-19.22.99-cp310-cp310-win_amd64.whl
```

Verify the installation:

```bash
python -c "import dlib; print(dlib.__version__)"
```

## Troubleshooting

Check your interpreter version and architecture with:

```bash
python --version
python -c "import platform, struct; print(platform.python_implementation(), platform.machine(), struct.calcsize('P') * 8)"
```

A wheel compatibility error usually means the Python version, ABI tag, or operating-system architecture does not match the filename. Use a compatible Python environment before installing.

## License and provenance

Review the repository's [LICENSE](LICENSE) and the upstream dlib project terms before redistributing this binary package. This repository does not claim that the wheel is a general-purpose or cross-platform dlib distribution.