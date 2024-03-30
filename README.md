# PIPX but with Conda

This is designed to install pipx-compatible packages with Conda. I created this
as a solution for using pipx on MacOS.

Requires:

- `conda`
- `python3`


## Example:

```bash
cx install git+https://github.com/mmngreco/takt
```


## Post

- TBD

## Using it


```bash
touch ~/.local/bin/cx
chmod +x ~/.local/bin/cx
```


and paste the content of the `cx` file into it.


## Gist

- https://gist.github.com/mmngreco/2ffa9738c64347f2942a7fa921ca93e1/raw/cx.py

You can use this through `pipx` by running the following command:
`pipx run https://gist.githubusercontent.com/mmngreco/2ffa9738c64347f2942a7fa921ca93e1/raw/cx.py`
