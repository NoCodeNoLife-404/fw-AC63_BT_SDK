LIBS = \
--start-group \
   $(AR_DIR)/cpu.a \
   $(AR_DIR)/system.a \
   $(AR_DIR)/btstack.a \
   $(AR_DIR)/btctrler.a \
   $(AR_DIR)/crypto_toolbox_Osize.a \
   $(AR_DIR)/agreement.a \
   $(AR_DIR)/rcsp_stack.a \
--end-group

LIBS += \
   $(AR_DIR)/update.a \

ifeq ($(AUDIO_LITE_VERSION),y)
LIBS += \
--start-group \
   $(AR_DIR)/aec.a \
   $(AR_DIR)/media.a \
   $(AR_DIR)/media_app.a \
   $(AR_DIR)/libAptFilt_pi32v2_OnChip.a \
   $(AR_DIR)/libEchoSuppress_pi32v2_OnChip.a \
   $(AR_DIR)/libNoiseSuppress_pi32v2_OnChip.a \
   $(AR_DIR)/libSplittingFilter_pi32v2_OnChip.a \
   $(AR_DIR)/libFFT_pi32v2_OnChip.a \
   $(AR_DIR)/libOpcore_maskrom_pi32v2_OnChip.a \
   $(AR_DIR)/lib_resample_cal.a \
   $(AR_DIR)/opus_enc_lib.a \
   $(AR_DIR)/speex_enc_lib.a \
   $(AR_DIR)/bfilterfun_lib.a \
   $(AR_DIR)/wtg_dec_lib.a \
   $(AR_DIR)/wtgv2_dec_lib.a \
   $(AR_DIR)/wav_dec_lib.a \
--end-group
endif

objs += \
	  $(ROOT)/apps/$(APP_CASE)/board/$(CPU)/board_ac636n_demo.o \
	  $(ROOT)/apps/$(APP_CASE)/board/$(CPU)/board_ac6368a_keyfob.o \
	  $(ROOT)/apps/$(APP_CASE)/board/$(CPU)/board_ac6369f_mouse.o \
	  $(ROOT)/apps/$(APP_CASE)/board/$(CPU)/board_ac6363f_mouse.o \
	  $(ROOT)/apps/$(APP_CASE)/board/$(CPU)/board_ac6366c_demo.o \
	  $(ROOT)/apps/$(APP_CASE)/board/$(CPU)/board_ac6369c_demo.o \
	  $(ROOT)/apps/$(APP_CASE)/board/$(CPU)/board_ac6368b_demo.o \
