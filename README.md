# Extended mdocfile

<p align="center" width="100%">
    <img width="70%" src="https://user-images.githubusercontent.com/7307488/205445941-8db4ad0e-648a-446e-812d-bd1b81ec19b8.png"> 
</p>

*Extended mdocfile* is Python package for working with [SerialEM](https://bio3d.colorado.edu/SerialEM/) mdoc files supplemented with extra columns of CtfFind mean defocus values (obtained with PACETomo DoCtffind function).

---

# Quickstart

`mdocfile.read()` will return the contents of an mdoc file as a pandas 
dataframe.

```python
import mdocfile

df = mdocfile.read('my_mdoc_file.mdoc')
```

# Installation

pip:

```shell
pip install mdocfile
```
