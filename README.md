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

┌──────────┬────┬──────┬──────┬─────────┬─────────┬────────┬─────┬──────────┬──────┬──────────┐
│ App name │ id │ mode │ pid  │ status  │ restart │ uptime │ cpu │ mem      │ user │ watching │
├──────────┼────┼──────┼──────┼─────────┼─────────┼────────┼─────┼──────────┼──────┼──────────┤
│ runDebug │ 1  │ fork │ 0    │ stopped │ 0       │ 0      │ 0%  │ 0 B      │ root │ disabled │
│ runGo    │ 0  │ fork │ 2596 │ online  │ 0       │ 8h     │ 0%  │ 1.9 MB   │ root │ enabled  │
│ yourapp  │ 2  │ fork │ 2601 │ online  │ 0       │ 8h     │ 0%  │ 1.7 MB   │ root │ enabled  │
└──────────┴────┴──────┴──────┴─────────┴─────────┴────────┴─────┴──────────┴──────┴──────────┘

tpm3 logs yourapp
```

# Contact the author

Join https://discord.gg/E2Xzbjx
to participate in the discussion and development.
