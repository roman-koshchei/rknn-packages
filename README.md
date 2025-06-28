# RKNN Packages

To work with RKNN through python you will need to use their packages, provided in [official repository](https://github.com/airockchip/rknn-toolkit2).

To simplify use I forked repository and only left packages files as well as default license.
No need to copy whole repository and easier to find those files.

Straightforward folder structure:

- `lite` - rknn-toolkit-lite2
- `arm64` - rknn-toolkit2 arm64
- `x86_64` - rknn-toolkit2 x86_64

## How to use

Go to file you want to use based on python version and architecture.
Copy raw link to the filed and then install it with python.

I use UV package manger and would recommend to everybody else.
Here is an example of command to install RKNN toolkit 2 on arm64:

```bash
uv add https://github.com/roman-koshchei/rknn-packages/raw/40a3df681ee7ea1d3540569264b53b447ac2d2f2/arm64/rknn_toolkit2-2.3.2-cp312-cp312-manylinux_2_17_aarch64.manylinux2014_aarch64.whl
```

You can also notice I use commit id instead of master branch, because it helps reproducibility.

**If you want, you can same way install it from official repository, no need to trust me!**

### Local file

You can also just download the wheel file to your local machine and even put it inside of the repository.
That's also a good way.
