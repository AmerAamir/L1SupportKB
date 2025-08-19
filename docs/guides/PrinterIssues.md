# Printer Issues

Steps to troubleshoot common printer problems.

## Check printer power and connections

1. Ensure the printer is turned on.
2. Verify that the USB or network cable is properly connected.

## Restart print spooler service (Windows)

Run the following commands in **Command Prompt**:

```sh
net stop spooler
net start spooler
```

## Add printer again

1. Open **Settings** > **Devices** > **Printers & scanners**.
2. Click **Add a printer or scanner** and follow the prompts.
