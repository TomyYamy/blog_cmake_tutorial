# Step 4

## How to run?

### package install

```bash
sudo apt install libeigen3-dev libgoogle-glog-dev
```

### build

```bash
mkdir build
cd build
cmake .. -DCeres_DIR='<path to directory of CeresConfig.cmake>'
cmake --build .
```
