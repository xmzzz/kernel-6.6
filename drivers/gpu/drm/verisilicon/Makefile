# SPDX-License-Identifier: GPL-2.0

vs_drm-objs := vs_dc_hw.o \
		vs_dc.o \
		vs_crtc.o \
		vs_drv.o \
		vs_fb.o \
		vs_gem.o \
		vs_plane.o \
		vs_simple_enc.o

vs_drm-$(CONFIG_VERISILICON_VIRTUAL_DISPLAY) += vs_virtual.o
vs_drm-$(CONFIG_VERISILICON_DW_MIPI_DSI) += dw_mipi_dsi.o
vs_drm-$(CONFIG_VERISILICON_DW_HDMI_TH1520) += dw_hdmi-th1520.o
vs_drm-$(CONFIG_VERISILICON_MMU) += vs_dc_mmu.o
vs_drm-$(CONFIG_VERISILICON_DEC) += vs_dc_dec.o

obj-$(CONFIG_DRM_VERISILICON) += vs_drm.o
