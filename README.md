# rpi-spi
Raspberry pi spi experiments

# imager-hat dependencies
imager requires: 
- packages:
    - libatlas-base-dev
    - libopenjp2-7
    - python3-pil
    - python3-numpy
    - python3-pip
    - python-rpi.gpio (button)
    - python3-rpi.gpio (button)
    - parted (for packer)
    - packer
- pip3 libraries:
    - adafruit-circuitpython-display-text==2.21.1
        - the latest version, 2.21.2, causes an 'undefined' error
    - adafruit-circuitpython-st7789
    - adafruit-blinka-displayio