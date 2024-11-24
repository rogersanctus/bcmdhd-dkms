# Introduction

This repo provides dkms source code for wireless adapters based on the Broadcom ap6xxx chipset.

Forked from BCMDHD 101.10.591.52.27 and adapted for the Rockchip platform.

---

## DKMS

This fork changes are specific for the SDIO module and adds a dkms.conf for bcmdhd-sdio module.

You can, of course, use this dkms.conf as base to build the other versions of the module: PCIE and USB.
