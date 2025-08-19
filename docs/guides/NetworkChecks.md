# Network Checks

Follow these steps to perform basic network connectivity checks.

## Check IP configuration

Run the following command in **Command Prompt**:

```sh
ipconfig /all
```

Review the IP address, subnet mask, and gateway.

## Ping the gateway

1. Identify your default gateway from the previous command.
2. Run:

```sh
ping <gateway_ip>
```

If the ping fails, there may be a local network issue.

## Test external connectivity

Run:

```sh
ping www.google.com
```

If this fails, test DNS resolution by using an IP address:

```sh
ping 8.8.8.8
```
