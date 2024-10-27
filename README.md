# 📉 rustem

```text
 ____               _
|  _ \  _   _  ___ | |_   ___  _ __ ___
| |_) || | | |/ __|| __| / _ \| '_ ` _ \
|  _ < | |_| |\__ \| |_ |  __/| | | | | |
|_| \_\ \__,_||___/ \__| \___||_| |_| |_|
```

📉 Rustem: A lightweight Rust library for system monitoring, providing CPU, memory, disk, and network statistics.

## ✨ Features

Rustem provides comprehensive system monitoring, offering real-time access to essential system metrics:

- **CPU Load**: Monitor current CPU usage to track processing demands.
- **Load Average**: Get average system load over configurable time intervals.
- **Memory Usage**: View real-time and total memory usage statistics.
- **Uptime & Boot Time**: Track system uptime and initial boot time.
- **Battery Life**: Access battery charge level and remaining time estimates.
- **Filesystem Mounts & Disk Usage**: List mounted filesystems and their usage.
- **Disk I/O Statistics**: View read/write operations and throughput for disks.
- **Network Interfaces**: Enumerate network interfaces and their configurations.
- **Network Traffic Statistics**: Monitor data sent/received through each network interface.
- **CPU Temperature**: Access current CPU temperature for system health insights.

Rustem is designed for lightweight performance, making it suitable for a wide range of monitoring applications.

### Supported platforms:

- FreeBSD
- Linux
- OpenBSD
- Windows
- macOS
- NetBSD
- _more coming soon_

## 🚀 Installation

To install **rustem**, simply clone the repository and follow the instructions below:

```bash
git clone git@github.com:trinhminhtriet/rustem.git
cd rustem

```

Running the below command will globally install the `rustem` binary.

```bash
cargo install rustem
```

## 💡 Usage

See [examples/info.rs](https://github.com/trinhminhtriet/rustem/blob/master/examples/info.rs).

## 🗑️ Uninstallation

Running the below command will globally uninstall the `rustem` binary.

```bash
cargo uninstall rustem
```

Remove the project repo

```bash
rm -rf /path/to/git/clone/rustem
```

## 🤝 How to contribute

We welcome contributions!

- Fork this repository;
- Create a branch with your feature: `git checkout -b my-feature`;
- Commit your changes: `git commit -m "feat: my new feature"`;
- Push to your branch: `git push origin my-feature`.

Once your pull request has been merged, you can delete your branch.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
