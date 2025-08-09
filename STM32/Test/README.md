- [Tutorial docs](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/get-started/linux-macos-setup.html)
   - Python virtual environment
   - pip install "esptool" and "setuptools"
   - Get ESP IDF extension
   - Mac
     - `brew install cmake ninja dfu-util ccache`
   - Make esp directory (do this in repo?)

# Flashing?
- `idf.py set-target esp32`
- `idf.py menuconfig`
- `idf.py -p /dev/cu.usbserial-0001 flash`
- 