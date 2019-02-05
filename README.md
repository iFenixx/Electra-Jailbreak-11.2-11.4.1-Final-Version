# Electra-Jailbreak-11.4-11.4.1-Final-Version


1.3.1 Changelog :

- Increase jailbreak success rate on A7 - A8 on 11.2+
- Update liboffsetfinder64 to latest version

1.3.0 Changelog :

- No longer require platformization to control launchd (requires tweaks switch enabled)
- Replace jailbreakd with jailbreakd2 (Next-gen fully-async jailbreakd with prioritization and a faster queuing system)
- jailbreakd2: Fix freezing in low memory conditions
- jailbreakd2: Faster ldrestarts, resprings
- jailbreakd2: XCode debugging success rate improved (click continue in the debugger on SIGCONT to proceed debugging)

1.2.7 Changelog :

Fix a bug in v1ntex that resulted a kernel panic later in Step 2
Actually test on an A7 device on 11.4 (thanks PastRestore on discord)

1.2.6 Changelog :

-Fix offsetfinder path issue for A7 & A8 devices on 11.4-11.4.1

1.2.5 Changelog :

- Fix sandbox issues causing app crash on A7 & A8 devices on 11.4-11.4.1
- Fix post-exploitation (stage 2) failures on A7 & A8 devices on 11.2 - 11.4.1

1.2.3 Changelog :

- Replace threadm1ll exploit with v1ntex for A7 & A8 devices on 11.2-11.4.1
- Fix initial ldrestart not working on some devices

1.2.2 Changelog :

- Fix async_wake so jailbreaking 11.0-11.1.2 works properly
- Fix nonce generator button not working

1.2.1 Changelog :

- Fix build number so 11.4 - 11.4.1 works properly

1.2.0 Changelog :

- Supports iOS 11.4 - 11.4.1
- Add async_wake exploit to add support for iOS 11.0 - 11.1.2
- Use voucher_swap exploit instead of empty_list for iOS 11.2 - 11.4.1
- Add threadm1ll exploit as an option for iOS 11.2 - 11.4.1 users on A7 or A8 devices
- Fix overnight reboots
- Reverted app to git commit 9d9762bdf46f19c4082d82798af41ca273fb0e37 before all code was rewritten from there forward
