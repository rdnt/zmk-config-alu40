# zmk-config-alu40

This is my ZMK keymap and configuration for the ALU40 keyboard.

- [ZMK Firmware](https://github.com/zmkfirmware/zmk)
- [ALU40 by huibenLAB](https://huibenlab.com/products/alu40-keyboard)

![image](https://github.com/user-attachments/assets/759c00fb-1edf-4e12-96aa-c434fd6e79ca)

## Instructions

1. [Fork this repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo#forking-a-repository).
2. [Click the **Actions** tab and make sure the workflow is enabled](https://docs.github.com/en/actions/managing-workflow-runs-and-deployments/managing-workflow-runs/disabling-and-enabling-a-workflow#enabling-a-workflow).
3. Make sure the `alu40-module` project in [`config/west.yml`](config/west.yml) still works. The `boards/arm/alu40` folder will be downloaded from this URL.
4. If there is still a `boards/arm/alu40` folder in your fork, delete it.

**If you already have a ZMK config repository, [you can add this one as a module instead of forking](https://zmk.dev/docs/features/modules#building-with-modules).**

## Notes

[`config/alu40.keymap`](config/alu40.keymap) contains [several reserved layers labeled `extra1-4`](https://zmk.dev/docs/features/studio#including-extra-layers) for use with [ZMK Studio](https://zmk.studio). If you intend to use [Keymap Editor](https://nickcoutsos.github.io/keymap-editor), these will need to be removed.

## Keymap

Keymap visualization created using [caksoylar/keymap-drawer](https://github.com/caksoylar/keymap-drawer)

![keymap](https://github.com/rdnt/zmk-config-alu40/assets/17600197/e360e3d5-24a3-4426-8ac6-f2a6aa3d9041)
