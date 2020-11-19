# stm32-test
Used for test and learning before implementing in real projects

# Compiling
You will need the arm-none-eabi toolchain: https://developer.arm.com/open-source/gnu-toolchain/gnu-rm/downloads
The only external depedency is libopencm3 which I forked. You can download and build this dependency by typing

`make get-deps`

Now you can compile stm32-test by typing

`make`

And upload it to your board using a JTAG/SWD adapter, the updater.py script or the esp8266 web interface
