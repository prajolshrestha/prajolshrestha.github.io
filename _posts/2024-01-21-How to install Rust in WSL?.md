---
layout: default
title: Rust in WSL
---
Once you have WSL installed, you can proceed with installing Rust:

1. Open WSL:

2. Update Package List:
```
sudo apt update
```

3. Install Dependencies:
```
sudo apt install build-essential
```

4. Download and Install Rust:
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

5. Configure Rust Environment:
````
source $HOME/.cargo/env
````

6. Verify Installation:
```
rustc --version
````

Now you should have Rust installed on your WSL instance. 
You can start using Rust by creating projects with cargo and writing Rust code with your favorite text editor or integrated development environment (IDE).






