# Ai-Thinker-Radar SDK
This SDK is applicable to the Ai-Thinker Rd-01 module.

## Clone The Repo
```
git clone --recurse-submodules https://github.com/Ai-Thinker-Open/Ai-Thinker-Radar.git
```
## Updated Permissions (If On Linux)
```
cd Ai-Thinker-Radar/Ai-Thinker-WB2/toolchain/riscv/Linux
. chmod755.shs
cd ../../../..
```
## Updated Permissions (If On MacOS)
```
cd Ai-Thinker-Radar/Ai-Thinker-WB2/toolchain/riscv/Darwin
bash ./chmod755.sh
cd ../../../..
```
## Apply Patches
```
cd Ai-Thinker-WB2
git apply ../patch/bfl_main.patch
cd ..
```
## Build The Project

```
cd Ai-Thinker-Radar/project
./genromap
```


