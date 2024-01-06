# React UI Components base on Shadcn UI

Usage:
```bash
git submodule [--quiet] add [-b <branch>] [-f|--force] [--name <name>] [--reference <repository>] [--] <repository> [<path>]
```

Help command:
```bash
git submodule --help
git submodule add --help
```

Example
```bash
git submodule add --branch main --name ui-components -- https://github.com/ravuthz/react-components.git src/components/ui
```

Clone or Pull with submodule
```bash
git pull --recurse-submodules
git clone --recurse-submodules <remote.url>

# Fixed module don't exists 
git submodule update --init --recursive
```
