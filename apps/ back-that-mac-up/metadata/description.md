# Time Machine

Time Machine is a backup solution compatible with Apple's Time Machine feature. It allows you to back up your macOS devices to a network drive using the SMB protocol.

## Purpose

Time Machine provides a simple and efficient way to back up your macOS devices to a network-attached storage (NAS) device. By using the SMB protocol, it ensures compatibility with macOS's built-in Time Machine backup system.

## Main Features

- **Network Backup**: Backup your macOS devices over the network using SMB, compatible with Apple's Time Machine.
- **User-Friendly**: Designed to be easy to set up and manage, providing a hassle-free backup solution.
- **Customizable**: Various configuration options allow you to tailor the setup to your specific needs.
- **Secure**: Implement security measures to protect your backups, including user authentication and access control.
- **Compatibility**: Works with macOS Time Machine, ensuring a seamless backup experience.

## Configuration Options

- **Advertised Hostname**: Set the hostname that will be advertised on the network.
- **Time Machine Username and Password**: Define the credentials for accessing the backup share.
- **User and Group IDs**: Customize the user and group IDs to match your system's configuration.

## Security

Time Machine includes several security features to protect your backups:

### User Authentication

Access to the backup share is protected by a username and password, ensuring that only authorized users can access the backups.

### Data Encryption

Data stored on the backup share can be encrypted to protect it against unauthorized access. It is recommended to use encrypted volumes to enhance security.

### Network Security

Time Machine uses the SMB protocol, which includes options for encrypted communication to protect data in transit.

## Usage

To use Time Machine, simply configure your macOS devices to use the network share provided by this service. The setup is straightforward and integrates seamlessly with the built-in Time Machine feature on macOS.

For more information and detailed setup instructions, please refer to the [source repository](https://github.com/mbentley/docker-timemachine).
