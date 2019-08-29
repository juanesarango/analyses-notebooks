## Indel Signatures 
Using [SigProfilerMatrixGenerator](https://github.com/AlexandrovLab/SigProfilerMatrixGenerator) package.

### Installation

To install python package
```bash
pip install SigProfilerMatrixGenerator
```

To install GRCh37
```python
from SigProfilerMatrixGenerator import install as genInstall
genInstall.install('GRCh37', rsync=False, bash=True)
```
