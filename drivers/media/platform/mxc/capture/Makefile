obj-$(CONFIG_VIDEO_MXC_CSI_CAMERA)	+= fsl_csi.o csi_v4l2_capture.o

ifeq ($(CONFIG_VIDEO_MXC_IPU_CAMERA),y)
	obj-$(CONFIG_VIDEO_MXC_CAPTURE) += mxc_v4l2_capture.o
	obj-$(CONFIG_MXC_IPU_PRP_VF_SDC) += ipu_prp_vf_sdc.o ipu_prp_vf_sdc_bg.o
	obj-$(CONFIG_MXC_IPU_DEVICE_QUEUE_SDC) += ipu_fg_overlay_sdc.o ipu_bg_overlay_sdc.o
	obj-$(CONFIG_MXC_IPU_PRP_ENC) += ipu_prp_enc.o ipu_still.o
	obj-$(CONFIG_MXC_IPU_CSI_ENC) += ipu_csi_enc.o ipu_still.o
endif

mxc_vadc_tvin-objs := mxc_vadc.o
obj-$(CONFIG_MXC_VADC) += mxc_vadc_tvin.o
