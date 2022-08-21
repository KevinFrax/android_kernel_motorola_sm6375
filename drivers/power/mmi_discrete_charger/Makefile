ccflags-y += -I$(srctree)/drivers/power/mmi_charger

mmi_discrete_charger-objs += mmi_discrete_charger_core.o
mmi_discrete_charger-objs += mmi_discrete_charger_iio.o
mmi_discrete_charger-objs += mmi_discrete_factory_tcmd.o
mmi_discrete_charger-objs += mmi_discrete_voter.o

obj-$(CONFIG_MMI_DISCRETE_CHARGER) += mmi_discrete_charger.o
obj-$(CONFIG_MMI_DISCRETE_CHARGER) += mmi_discrete_charger_class.o
