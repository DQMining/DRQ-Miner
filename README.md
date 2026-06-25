# DRQ Miner

Production releases from [DQMining](https://www.dqmining.com).

**Downloads:** [Releases](https://github.com/DQMining/DRQ-Miner/releases)

| Asset | Platform |
|-------|----------|
| `DRQMiner-win64.zip` | Windows x64 |
| `drqminer-linux-x64.tar.gz` | Linux x64 |
| `drqminer-linux-arm64-phone.tar.gz` | Android Userland (arm64) |

```bash
TAG=v1.0.10   # use latest tag from Releases
wget "https://github.com/DQMining/DRQ-Miner/releases/download/${TAG}/drqminer-linux-x64.tar.gz"
tar xzf drqminer-linux-x64.tar.gz && chmod +x drqminer
./drqminer -V
```

**Example (nm/1):**

```bash
./drqminer -a nm/1 -o POOL:12427 -u WALLET.WORKER -p x
```

Stable builds **auto-install** stable updates only. Default dev donation **3%** (`--donate-level=0` to disable).

**Other channels:** [Beta](https://github.com/DQMining/DRQ-Miner-Beta) · [Alpha testing](https://github.com/DQMining/DRQ-Miner-Testing)

[Discord](https://discord.gg/Nku5N3WSBm)
