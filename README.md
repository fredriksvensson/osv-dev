# osv-dev
An environment to develop OSv

The purpouse of this vagrant box is to make an image that act as a baseline for further development of erlang on OSv.

# Howto
Build the image with
`scripts/build image=erlang`

Run using qemu by issuing the line
`scripts/run.py -m 128M`

This will restrict the memory to 128M, otherwise qemu will be use up all memory and crash.

