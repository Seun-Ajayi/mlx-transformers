# Contributing to mlx-transformers

Contributions to mlx-transformers are welcome. We need help to improve the library and add more models, adding examples and documentation, and fixing bugs.

## Pull Requests

1. Fork and submit pull requests to the repo. 
2. If you've added code that should be tested, add tests.
3. Every PR should have passing tests and at least one review. 
4. For code formatting install `pre-commit` using something like `pip install pre-commit` and run `pre-commit install`.
   This should install hooks for running `black` and `clang-format` to ensure
   consistent style for C++ and python code.
 
   You can also run the formatters manually as follows on individual files:
 

     ```bash
     # single file
     pre-commit run --files file1.py 

     # specific files
     pre-commit run --files file1.py file2.py
     ```
 
   or run `pre-commit run --all-files` to check all files in the repo.

## Issues

We use GitHub issues to track public bugs. Please ensure your description is
clear and has sufficient instructions to be able to reproduce the issue.

## License

By contributing to mlx-transformers, you agree that your contributions will be licensed
under the LICENSE file in the root directory of this source tree.
