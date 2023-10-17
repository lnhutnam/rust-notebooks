# Rust Notebooks

## Setup anaconda

Creating anaconda environment (I use Python 3.9)

```bash
conda env create -f environment.yml

conda activate rust-notebooks
```

## Setup Rust

Install Rust

Option 00

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Optional 01 (For Arch users)

```bash
sudo pacman -Sy rust
```

Optional 02 (For Arch users)

```bash
sudo pacman -Sy rustup
```

Then

```bash
rustup default stable
```

```bash
rustup component add rust-src
```

## Setup jupyter kernel for Rust

```bash
cargo install evcxr_jupyter
```

```bash
evcxr_jupyter --install
```

# Start

```bash
jupyter notebook
```

