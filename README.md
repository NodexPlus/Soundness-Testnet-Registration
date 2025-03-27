Link: https://soundness.xyz/
Register for Testnet
sudo apt update && sudo apt upgrade -y
sudo apt-get install curl wget git screen jq libpq-dev libssl-dev \
build-essential pkg-config openssl ocl-icd-opencl-dev \
libopencl-clang-dev libgomp1 apparmor-profiles -y
1. curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
2. source ~/.bashrc # for bash
3. curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
Type 1 and press Enter
4. source $HOME/.cargo/env
5. soundnessup install # Install the CLI
6. soundness-cli generate-key --name my-key
enter your password and press enter (the password won't show as you're entering it) Now, write down the 24 mnemonic phrase and copy your public key
