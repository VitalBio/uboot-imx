
ccflags-y += -I$(srctree)/board/compulab/plat/imx8mp/
ccflags-y += -I$(srctree)/board/compulab/plat/imx8/
ccflags-y += -I$(srctree)/board/compulab/common/

ifdef CONFIG_SPL_BUILD
obj-y += spl.o
else
obj-y += cerebro.o
endif

obj-y += ../../compulab/plat/imx8mp/
obj-y += ../../compulab/plat/imx8/
obj-y += ../../compulab/common/
