ccflags-y += -Idrivers/media/platform/msm/camera_v2
ccflags-y += -Idrivers/media/platform/msm/camera_v2/common
ccflags-y += -Idrivers/media/platform/msm/camera_v2/sensor/io
ccflags-y += -Idrivers/media/platform/msm/camera_v2/sensor/cci
ifeq ($(BUILD_OPTION_FACTORY_BUILD),true)
  ccflags-y += -DCONFIG_VSM_FACTORY_BIN
endif
obj-$(CONFIG_MSM_EEPROM) += msm_eeprom.o
