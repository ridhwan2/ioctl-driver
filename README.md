# Information
- Compiling the project requires [Visual Studio](https://visualstudio.microsoft.com/downloads/) & the [WDK](https://learn.microsoft.com/en-us/windows-hardware/drivers/download-the-wdk#download-icon-for-wdk-step-3-install-wdk).
- The offsets are up to date as of [...](https://steamdb.info/changelist/23684880/)
- The driver can be mapped using [kdmapper](https://github.com/TheCruZ/kdmapper).
- Tested on Windows 11 (22631.3593)

## Misc
- Assuming that you are only reading and not writing memory, and the cheat functionality remains within the kernel there shouldn't be any problems with VAC or any other other usermode anticheat.
- However, this driver should never be mapped or present within the operating system while an anticheat like EAC, Battle-Eye, Vanguard, Faceit, Richochet, [etc](https://levvvel.com/games-with-kernel-level-anti-cheat-software/) are running.
- This project is more of a base than a fully usable software, it can be used to learn or be developed further.

## Credits
- [youtube](https://www.youtube.com/results?search_query=how+to+make+a+kernel+driver). For the driver.
- [dumper](https://github.com/a2x/cs2-dumper). For offsets.
- [uc](https://www.unknowncheats.me/forum/counter-strike-2-a/606947-bomb-esp-help.html). Checking weather the bomb is planted or not. 


## License
> [MIT](https://opensource.org/license/mit) ridhwan 2024
> - [x] I have read the above.
