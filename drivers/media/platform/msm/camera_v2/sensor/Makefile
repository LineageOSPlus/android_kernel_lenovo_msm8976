GCOV_PROFILE := y
ccflags-y += -Idrivers/media/platform/msm/camera_v2
ccflags-y += -Idrivers/media/platform/msm/camera_v2/msm_vb2
ccflags-y += -Idrivers/media/platform/msm/camera_v2/camera
ccflags-y += -Idrivers/media/platform/msm/camera_v2/sensor/io
ccflags-y += -Idrivers/media/platform/msm/camera_v2/sensor/cci
obj-$(CONFIG_MSMB_CAMERA) += cci/ io/ csiphy/ csid/ actuator/ flash/ eeprom/ ois/
obj-$(CONFIG_MSM_CAMERA_SENSOR) += msm_sensor_init.o msm_sensor_driver.o msm_sensor.o
#modified by luzhenfei 2016-04-08 disable obsoleting code
#obj-$(CONFIG_MT9M114) += mt9m114.o
#obj-$(CONFIG_OV5645) += ov5645.o
#obj-$(CONFIG_OV2685) += ov2685.o
#obj-$(CONFIG_OV2685_SCV3B4035) += ov2685_scv3b4035.o
#obj-$(CONFIG_OV5645) += ov7695.o
#obj-$(CONFIG_GC0310) += gc0310.o
