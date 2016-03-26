ccflags-y := -O2 -ffast-math -fgcse-lm -fgcse-sm -fsched-spec-load -fforce-addr -fsingle-precision-constant -march=armv7-a -mtune=cortex-a7 -mfloat-abi=hard -mfpu=neon-vfpv4 -marm
obj-$(CONFIG_ION) +=	ion.o ion_heap.o ion_page_pool.o ion_system_heap.o \
			ion_carveout_heap.o ion_chunk_heap.o
obj-$(CONFIG_CMA) += ion_cma_heap.o
obj-$(CONFIG_MM_SECURE_DRIVER) += ion_secure_heap.o
obj-$(CONFIG_ION_TEGRA) += tegra/
obj-$(CONFIG_ION_BCM) += bcm/
