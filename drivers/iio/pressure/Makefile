#
# Makefile for industrial I/O pressure drivers
#

# When adding new entries keep the list in alphabetical order
obj-$(CONFIG_HID_SENSOR_PRESS)   += hid-sensor-press.o
obj-$(CONFIG_MPL115) += mpl115.o
obj-$(CONFIG_MPL3115) += mpl3115.o
obj-$(CONFIG_IIO_ST_PRESS) += st_pressure.o
st_pressure-y := st_pressure_core.o
st_pressure-$(CONFIG_IIO_BUFFER) += st_pressure_buffer.o
obj-$(CONFIG_T5403) += t5403.o

obj-$(CONFIG_IIO_ST_PRESS_I2C) += st_pressure_i2c.o
obj-$(CONFIG_IIO_ST_PRESS_SPI) += st_pressure_spi.o

obj-$(CONFIG_ST_LPS22HB_IIO) += st_lps22hb.o
obj-$(CONFIG_ST_LPS22HB_I2C_IIO) += st_lps22hb_i2c.o
obj-$(CONFIG_ST_LPS22HB_SPI_IIO) += st_lps22hb_spi.o

st_lps22hb-y += st_lps22hb_core.o st_lps22hb_buffer.o

obj-$(CONFIG_ST_LPS33HW_IIO) += st_lps33hw.o
obj-$(CONFIG_ST_LPS33HW_I2C_IIO) += st_lps33hw_i2c.o
obj-$(CONFIG_ST_LPS33HW_SPI_IIO) += st_lps33hw_spi.o

st_lps33hw-y += st_lps33hw_core.o st_lps33hw_buffer.o

obj-$(CONFIG_ST_LPS22HH_IIO) += st_lps22hh.o
obj-$(CONFIG_ST_LPS22HH_I2C_IIO) += st_lps22hh_i2c.o
obj-$(CONFIG_ST_LPS22HH_SPI_IIO) += st_lps22hh_spi.o

st_lps22hh-y += st_lps22hh_core.o st_lps22hh_buffer.o
