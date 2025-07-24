# Python3.13-Portable-Image
A precompiled image that contains the Python3.13 interpreter, especially for use in VMs or GitHub Codespaces.

To use, clone this repo:

```
git clone https://github.com/The-CS-Nerds/Python3.13-Portable-Image.git
```

Enter the cloned directory and extract the archive:

```
cd Python3.13-Portable-Image/
tar -xf python-3.13.5-portable.tar.lzma
```

You should now have a Python3.13 interpreter in `Python3.13-Portable-Image/python3.15.5-portable/bin`.

You can add this instance to be globally accessible by adding it to your `PATH` - you will need the absolute path of `Python3.13-Portable-Image/python3.15.5-portable/bin`.

```
export "[insert absolute path]:$PATH"
```

You should now be able to use `python3` or `python3.13` to access the Python3.13 interpreter - just don't delete the `Python3.13-Portable-Image` folder.

We recommend you add this folder to your `.gitignore` - add the line below into your `.gitignore` file so it isn't tracked by Git.

```
Python3.13-Portable-Image/
```
