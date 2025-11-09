# sandman

Repository holding C++ and Python components.

Structure
- src/: C++ library and apps (built via CMake)
- python/: Python package(s)
- bindings/: optional pybind11 bindings compiled into a Python extension
- tests/: unit tests for C++ and Python

Build (example)
- C++: `cmake -S . -B build && cmake --build build`
- Python: `python -m venv venv && source venv/bin/activate && pip install -r requirements.txt && pip install -e python`

License: MIT