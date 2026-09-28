# Pterodactyl Eggs

A collection of eggs for obscure decomp/recomp ports of games with their custom dedicated servers, designed to run on Pterodactyl. These eggs were created with the assistance of AI, so they are by no means the best possible implementations. However, they have been tested and work reliably for daily use.

These eggs are designed to make installing and running dedicated servers through Pterodactyl simple. Import the desired egg into your Pterodactyl Panel, create a server using that egg, assign the required port, and start the server.

## Included Eggs

* **Hydro Thunder Online** — Dedicated master server
* **GoldenEye 64 / GoldenEye Recompiled** — Dedicated server
* Additional eggs may be added over time.

## Installation

### 1. Download an Egg

Download the `.json` file for the server you want to install.

### 2. Import the Egg

In Pterodactyl:

1. Open the **Admin Panel**
2. Go to **Nests**
3. Select the Nest you want to use
4. Select **Import Egg**
5. Upload the desired `.json` egg file

### 3. Create the Server

Create a new server and select the imported egg.

Assign the required allocation/port for that server.

> **Note:** Port requirements vary between games. Check the individual egg or its documentation for the required port and protocol.

### 4. Start the Server

Start the server from the Pterodactyl Panel.

The egg's installation script will automatically download and configure the required server files when applicable.

## Requirements

* Pterodactyl Panel
* Pterodactyl Wings
* A compatible Docker image/runtime specified by the egg
* Required network ports/allocations

## Backup Ports

The [`BackupsOfPorts`](https://github.com/DaedheldirPR/Personal-Pterodactyl-Eggs/tree/main/BackupsOfPorts) folder contains backup copies of game ports and related projects that **were not created or developed by me**. They are included solely for preservation and backup purposes.

These projects remain the work of their respective authors and are included in accordance with their applicable licenses, including the **MIT License** and **The Unlicense**. Original credits, license files, and notices have been retained where applicable.

The backups contain **only the base port/server program files** and do **not** include game ROMs, ISOs, game assets, proprietary game files, or other copyrighted game content. They are intended to preserve the software projects themselves without distributing the original games or their associated content.

These backups are intended to preserve working versions of these projects in case their original repositories are deleted, become unavailable, or are otherwise inaccessible. When an original repository is available, please refer to and support the original project and its creators.

## Credits

These eggs may use server software created by their respective original developers. All third-party software remains under its original license.

This repository contains **unofficial Pterodactyl eggs** and is not affiliated with the developers or publishers of the games or server software included.

## License

The Pterodactyl eggs, installation scripts, and configuration created for this repository are provided under the **MIT License**.

Third-party server software included with or downloaded by an egg remains under its respective original license.
