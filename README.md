# Ducky-Scripts
A collection of evil USB rubber ducky scripts (all compatible with pico-ducky as well!)
- - - -
These scripts are for education purposes only, and I don't condone using these without permission.

## Getting started!
You will need one of the following:
A [USB Rubber Ducky](https://shop.hak5.org/products/usb-rubber-ducky)
Alternatively (cheaper)
A [Pico-Ducky](https://github.com/dbisu/pico-ducky)
- - - -
### Adding the scripts
Download a script from [here](https://github.com/zek-c/Ducky-Scripts/Scripts), or make your own (learn how [here](https://docs.hak5.org/hak5-usb-rubber-ducky/ducky-script-basics/hello-world))
<details>
<summary>If using a USB Rubber Ducky</summary>
Convert the .txt file to `inject.bin'
Then, copy it to the root of the drive. (If on linux, it should be `/dev/sdX` where `X` is the USB ducky's drive letter, and no following subdirectories, if on windows, it should be `${Drive Letter}:/ and no subdirectories)
</details>
<details>
<summary>If using a Pico-Ducky</summary>
Convert the .txt file to `payload.dd` 
Then, copy it to the root of the drive. (If on linux, it should be `/dev/sdX` where `X` is the USB ducky's drive letter, and no following subdirectories, if on windows, it should be `${Drive Letter}:/ and no subdirectories)
</details>
<br>
When ready, insert the drive into the targets computer. Make sure the operating system matches the scripts' target, or else unexpected things could happen.
Refer to the proper guides to plug in a USB in programming mode, to make sure it doesn't execute on a computer you don't want it to.
