include $(srctree)/drivers/misc/mediatek/Makefile.custom

obj-y   +=  mt65xx_lcm_list.o

# Nishil added Config Macro as below
obj-y   +=  hx8389b_qhd_dsi_vdo.o
obj-y   +=  otm9605a_qhd_dsi_vdo.o

ifeq ($(CONFIG_CUSTOM_KERNEL_LCM),"nt35590_hd720_dsi_cmd_auo")
obj-y   +=  nt35590_hd720_dsi_cmd_auo.o
endif

ifeq ($(CONFIG_CUSTOM_KERNEL_LCM),"nt35590_hd720_dsi_cmd_auo_wvga")
obj-y   +=  nt35590_hd720_dsi_cmd_auo_wvga.o
endif

#ifeq ($(CONFIG_CUSTOM_KERNEL_LCM),"nt35590_hd720_dsi_cmd_auo_fwvga")
#obj-y   +=  nt35590_hd720_dsi_cmd_auo_fwvga.o
#endif

ifeq ($(CONFIG_CUSTOM_KERNEL_LCM),"nt35590_hd720_dsi_cmd_auo_qhd")
obj-y   +=  nt35590_hd720_dsi_cmd_auo_qhd.o
endif