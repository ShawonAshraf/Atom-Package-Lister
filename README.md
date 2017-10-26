# Atom-Package-Getter

## Why though?
I recently started using atom and the first problem I faced was, I need to have the same set of packages installed on all my computers. So searched around the internet and found [this](https://goo.gl/KHR7YW) one in Atom forums. Was useful, so thought of writing bash scripts to make it easier to extract package names and install as well.

## Usage

- `get_packages.sh` gets the packages installed and saves them in the file `package_list.txt`.
- To run the script, make it executable first, then run.

```bash
#use sudo if there's
#permission error
chmod +x get_packages.sh

./get_packages.sh
```

- Now you have your `package_list.txt`, you can copy it to another computer and run:

```bash
#use sudo if there's
#permission error
chmod +x install_package.sh
./install_package.sh
```
