# PyTorch-Complex

Complex-valued tensor support for [PyTorch](https://github.com/pytorch/pytorch). (Work in progress)

**Warning**: This package is at very early stage, do not use it.

## Usage

**Warning**: this package requires a fresh build of PyTorch
revision 6cb593b88cb0c411690b4957850058329526d87b.  Other
revisions may work, but you will void the warranty.

To use this commit, `git clone` pytorch and checkout to this commit, then build pytorch from soruce.
After you build PyTorch successfully, you will be able to build this plugin just like a normal Python package:

```sh
python setup.py install
python setup.py build
python setup.py test
```

```python
from torch_complex import torch
```

or

```python
import torch_complex.torch as torch
```

then the complex tensor support will be in `torch` module. Use it just like the other tensor types.

## Contribution

Please read [Pytorch/#755](https://github.com/pytorch/pytorch/issues/755) first.
