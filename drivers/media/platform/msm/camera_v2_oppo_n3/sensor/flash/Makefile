ccflags-y += -Idrivers/media/platform/msm/camera_v2_oppo_n3
ccflags-y += -Idrivers/media/platform/msm/camera_v2_oppo_n3/sensor/io
ccflags-y += -Idrivers/media/platform/msm/camera_v2_oppo_n3/sensor/cci
ifeq ($(CONFIG_OPPO_DEVICE_FIND7),y)
obj-$(CONFIG_MSMB_CAMERA) += msm_led_cci.o
endif
obj-$(CONFIG_MSMB_CAMERA) += msm_led_flash.o
obj-$(CONFIG_MSMB_CAMERA) += msm_led_trigger.o
#obj-$(CONFIG_MSMB_CAMERA) += msm_led_i2c_trigger.o
#obj-$(CONFIG_MSMB_CAMERA) += adp1660.o
obj-$(CONFIG_MSMB_CAMERA) += msm_led_torch.o
