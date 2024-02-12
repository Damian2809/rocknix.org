# Game Console R33S/R35S/R36S

![](../../_inc/images/devices/unbranded-game-console-r33s.png){ .off-glb }

## Overview

| Device | CPU / Architecture | Kernel | GL driver | Interface |
| -- | -- | -- | -- | -- |
| R33S | Rockchip RK3326 (ARM) | Mainline Linux | Panfrost | Weston + Emulation Station |
| R35S | Rockchip RK3326 (ARM) | Mainline Linux | Panfrost | Weston + Emulation Station |
| R36S | Rockchip RK3326 (ARM) | Mainline Linux | Panfrost | Weston + Emulation Station |

## Controls

{%set btn_north = 'Y(NORTH)' %}
{%set btn_west = 'X(WEST)' %}
{%set btn_south = 'A(SOUTH)' %}
{%set btn_east = 'B(EAST)' %}

{%include 'controls/retroarch.md' %}
{%include 'controls/mednafen.md' %}

{%set btn_pre1 = 'SELECT' %}
{%set btn_pre2 = 'START' %}
{%include 'controls/extra.md' %}

## Emulators

- [Platform Documentation (RK3326)](https://github.com/JustEnoughLinuxOS/distribution/blob/main/documentation/PER_DEVICE_DOCUMENTATION/RK3326)

## Notes

### Installation

Download the latest `RK3326` version of JELOS from the button below and follow the instructions listed on the [Install](../../../play/install/) page.

[![Latest Version](https://img.shields.io/github/release/JustEnoughLinuxOS/distribution.svg?labelColor=111111&color=5998FF&label=Latest&style=flat#only-light)](https://github.com/JustEnoughLinuxOS/distribution/releases/latest)
[![Latest Version](https://img.shields.io/github/release/JustEnoughLinuxOS/distribution.svg?labelColor=dddddd&color=5998FF&label=Latest&style=flat#only-dark)](https://github.com/JustEnoughLinuxOS/distribution/releases/latest)
