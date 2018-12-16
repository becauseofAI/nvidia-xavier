# Installing JetPack
## Requirements
Supported host operating systems are Ubuntu Linux x64 Version 18.04 or 16.04

## Download Installer to Host Computer
1. Download JetPack 4.1 from https://developer.nvidia.com/embedded/downloads

2. Move binary into installation directory, /home/$USER/JetPack-L4T/ is recommended

```shell
mkdir -p /home/$USER/JetPack-L4T/
mv JetPack-${VERSION}.run /home/$USER/JetPack-L4T/
```

3. Set the Jetpack binary as executable and set correct permissions.

```shell
cd /home/$USER/JetPack-L4T
chmod +x JetPack-${VERSION}.run
```

## Run the Installer
1. Run the Binary

```shell
./JetPack-${VERSION}.run
```