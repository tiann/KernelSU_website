# FAQ

## Does KernelSU support my device?

First, your devices should be able to unlock the bootloader. If it can't, then it is unsupported.

Then install KernelSU manager App to your device and open it, if it shows `Unsupported` then your device is unsupported and won't be supported in the future.

## Does KernelSU need to unlock Bootloader?

Certainly, yes.

## Will KernelSU support modules?

Yes. We are working on it!

## Does KernelSU support Xposed?

Yes. It is WIP.

## Is KernelSU compatible with Magisk?

Yes. KernelSU modify the `kernel` and Magisk modify the `ramdisk`, they can work together.

## Will KernelSU substitute Magisk?

We don't think so and it's not our goal. Magisk is good enough for userspace root solution and it will live long. KernelSU's goal is to provide a kernel interface to users, not substituting Magisk.

## Can KernelSU support non GKI devices?

It is possible. But you should download the kernel source and intergrate KernelSU to the source tree and compile the kernel yourself.