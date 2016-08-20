# RebootInWindows
Short script to reboot a Mac into its Windows partition

Set the `BOOTPART` variable to the name of the Bootcamp partition (linux or mac)

Set the `EFI` variable to `true` or `false` based on whether you want the system to use the modern EFI
or an emulated legacy BIOS

Add this script to the `sudoers` file to allow it to run without a password.

Made possible by the work of @jwhitley and @robjwells in [this gist](https://gist.github.com/jwhitley/8377268)
