CFLAGS_trace.o			:= -I$(src)

obj-$(CONFIG_TYPEC_UCSI)	+= typec_ucsi.o

typec_ucsi-y			:= ucsi.o

typec_ucsi-$(CONFIG_FTRACE)	+= trace.o

obj-$(CONFIG_UCSI_ACPI)		+= ucsi_acpi.o

obj-$(CONFIG_UCSI_CCG)		+= ucsi_ccg.o
