# dotfiles

## About <a name = "about"></a>

Generally used dotfiles repository.

### Prerequisites

What things you need to install the software and how to install them.

[oh my bash](https://github.com/ohmybash/oh-my-bash)

-   It makes bash terminal beautiful.

```bash
bash -c "$(wget https://raw.githubusercontent.com/ohmybash/oh-my-bash/master/tools/install.sh -O -)"
```

> **Note:** If you execute above command, your '.bashrc' is replaced to '.bashrc.omb-backup-${DATE}'

[autojump](https://github.com/wting/autojump)

-   You can jump any directory easily that you have been visited.

```bash
sudo apt-get install autojump
```

### Installing

1. Download bashprofile to my workspace

    ```bash
    wget https://raw.githubusercontent.com/mqjinwon/dotfiles/main/bashprofile -q -O ~/bashprofile
    ```

2. Setting bashprofile to my `~/.bashrc`

    ```bash
    echo source ~/bashprofile >> ~/.bashrc
    ```
