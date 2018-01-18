# TPM3
Tiny production process manager for Linux.  
Pure Golang wrote.

# Feature
- Have the classic features of PM2, but use minimal memory and CPU, no dependencies.
- When the program crashes, it automatically restarts and pushes notifications to your phone.
- Watch source changes, compile and run automatically.
- Real-time display process logs.
- Automatically resume the process of management when Linux reboot.


# Usage
The simplest way to start, daemonize and monitor your application is by using this command line:

```
tpm3 start ./yourapp
tpm3 logs yourapp
```

# Contact the author

Join https://discord.gg/E2Xzbjx
to participate in the discussion and development.
