# ⚡️PPA

FarsFusion PPA hosted on GitHub

## 🚦Usage

Open a terminal window and enter the following command to add the PPA to apt:

```shell
curl -fsSL https://farsfusion.github.io/ppa/ubuntu/KEY.gpg | sudo gpg --dearmor -o /usr/share/keyrings/farsfusion-archive-keyring.gpg
```

```shell
echo "deb [signed-by=/usr/share/keyrings/farsfusion-archive-keyring.gpg] https://farsfusion.github.io/ppa/ubuntu ./" | sudo tee /etc/apt/sources.list.d/farsfusion.list
```

```shell
sudo apt update

# Sample
sudo apt cyruspass
```

## 📦Packages

The following packages are available in the PPA:

- `cyruspass` - A simple CLI password generator

## 📢License

MIT
