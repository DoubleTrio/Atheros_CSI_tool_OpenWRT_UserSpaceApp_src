# Command Usages

One router should run `recvCSI`
The other should run `sendData` (send `<n>` total packages) or `sendDataLoop` (send a package every `<μs>` microsecond)

## recvCSI

Run `make` in the recvCSI directory

Usage: 
* `./recvCSI <output_file>`

Example:
* `./recvCSI output.log`

## sendData

Run `make` in the sendData directory
* `./sendData <interface> <dstMacAddr> <numPacketsToSend>`
* `./sendDataLoop <interface> <dstMacAddr> <interval>`

Example:
* `./sendData wlan0 00:7F:5D:3E:4A 100`
* `./sendDataLoop wlan0 00:7F:5D:3E:4A 50`