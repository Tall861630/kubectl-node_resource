# kubectl-node_resource

![GitHub Repo Stars](https://img.shields.io/github/stars/Tall861630/kubectl-node_resource?style=social)
![GitHub Release](https://img.shields.io/github/release/Tall861630/kubectl-node_resource.svg)

## Overview

Welcome to the **kubectl-node_resource** repository! This tool helps you query node allocations and utilization in your Kubernetes clusters using `kubectl`. With this plugin, you can gain insights into how resources are distributed across your nodes, helping you manage your cluster more effectively.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Commands](#commands)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Resource Monitoring**: Easily check the resource allocation and utilization of your nodes.
- **Integration with kubectl**: Seamlessly integrates as a plugin to your existing `kubectl` setup.
- **User-Friendly Interface**: Simple commands that provide clear outputs.
- **Customizable Queries**: Tailor your queries to get the exact information you need.

## Installation

To install the kubectl-node_resource plugin, download the latest release from [here](https://github.com/Tall861630/kubectl-node_resource/releases). After downloading, execute the file to set up the plugin in your environment.

```bash
# Example command to install
chmod +x ./kubectl-node_resource
sudo mv ./kubectl-node_resource /usr/local/bin/kubectl-node_resource
```

Ensure you have the necessary permissions to move the file to your `PATH`.

## Usage

After installation, you can start using the plugin by typing `kubectl node_resource` in your terminal. This command will provide you with an overview of your node resources.

For more detailed information on usage, refer to the commands section below.

## Commands

Here are some of the primary commands you can use with kubectl-node_resource:

### `kubectl node_resource list`

This command lists all nodes along with their resource allocations and current utilization.

```bash
kubectl node_resource list
```

### `kubectl node_resource details <node-name>`

Get detailed information about a specific node by replacing `<node-name>` with the name of the node you wish to query.

```bash
kubectl node_resource details node1
```

### `kubectl node_resource usage`

View the overall resource usage across all nodes.

```bash
kubectl node_resource usage
```

### `kubectl node_resource help`

Get help on using the plugin and view available commands.

```bash
kubectl node_resource help
```

## Contributing

We welcome contributions to improve the kubectl-node_resource plugin. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your forked repository.
5. Open a pull request.

Please ensure your code follows the existing style and includes appropriate tests where applicable.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or issues, feel free to reach out via the GitHub issues page or directly contact me at [your-email@example.com].

---

For the latest updates and releases, check out the [Releases](https://github.com/Tall861630/kubectl-node_resource/releases) section.

Happy querying! 🚀