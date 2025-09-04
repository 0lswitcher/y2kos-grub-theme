## 0lOS GRUB theme

Forked from [shvchk's](https://github.com/shvchk) [Fallout GRUB Theme](https://github.com/shvchk/fallout-grub-theme).  

Mostly just changed the background, added more icons, and updated the config (theme.txt) a bit.  

Supported languages: Chinese (simplified), Chinese (traditional), English, French, German, Hungarian, Italian, Korean, Latvian, Norwegian, Polish, Portuguese, Russian, Rusyn, Spanish, Turkish, Ukrainian

<p align="center">
  <img src="https://github.com/0lswitcher/0los-grub-theme/blob/main/md-assets/IMAGE.png"
   style="width: 50%; height: 50%">
</p>

---


### Installation / update

- **Secure way:**

  - Download install script:

    ```sh
    wget -P /tmp https://github.com/shvchk/fallout-grub-theme/raw/master/install.sh
    ```

  - Review it at `/tmp/install.sh`

  - Run it:

    ```sh
    bash /tmp/install.sh
    ```

- **Easier, less secure way** — just download and run install script:

  ```sh
  wget -O - https://github.com/shvchk/fallout-grub-theme/raw/master/install.sh | bash
  ```

<br>

You can use `--lang` option to select language and disable interactive language selection, e.g.:

```sh
bash /tmp/install.sh --lang German
```

or

```sh
wget -O- https://github.com/shvchk/fallout-grub-theme/raw/master/install.sh | bash -s -- --lang Korean
```

Full list of languages see in `INSTALLER_LANGS` variable in [install.sh](install.sh)

---

### Credit

- [Fallout GRUB Theme](https://github.com/shvchk/fallout-grub-theme)
