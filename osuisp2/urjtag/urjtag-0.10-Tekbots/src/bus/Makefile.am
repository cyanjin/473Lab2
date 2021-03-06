#
# $Id: Makefile.am 1417 2009-01-03 20:09:31Z arniml $
#
# Copyright (C) 2003 ETC s.r.o.
#
# This program is free software; you can redistribute it and/or
# modify it under the terms of the GNU General Public License
# as published by the Free Software Foundation; either version 2
# of the License, or (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program; if not, write to the Free Software
# Foundation, Inc., 59 Temple Place - Suite 330, Boston, MA
# 02111-1307, USA.
#
# Written by Marcel Telka <marcel@telka.sk>, 2003.
#

include $(top_srcdir)/Makefile.rules

noinst_LIBRARIES = libbus.a

libbus_a_SOURCES = \
	buses.c \
	buses.h \
	generic_bus.c \
	generic_bus.h \
	pxa2x0_mc.h \
	readmem.c \
	writemem.c

if ENABLE_BUS_AU1500
libbus_a_SOURCES += au1500.c
endif

if ENABLE_BUS_AVR32
libbus_a_SOURCES += avr32.c
endif

if ENABLE_BUS_BCM1250
libbus_a_SOURCES += bcm1250.c
endif

if ENABLE_BUS_BF526_EZKIT
libbus_a_SOURCES += bf537_stamp.c
endif

if ENABLE_BUS_BF527_EZKIT
libbus_a_SOURCES += bf537_stamp.c
endif

if ENABLE_BUS_BF533_STAMP
libbus_a_SOURCES += bf533_stamp.c
endif

if ENABLE_BUS_BF533_EZKIT
libbus_a_SOURCES += bf533_ezkit.c
endif

if ENABLE_BUS_BF537_STAMP
libbus_a_SOURCES += bf537_stamp.c
endif

if ENABLE_BUS_BF537_EZKIT
libbus_a_SOURCES += bf537_stamp.c
endif

if ENABLE_BUS_BF538F_EZKIT
libbus_a_SOURCES += bf537_stamp.c
endif

if ENABLE_BUS_BF548_EZKIT
libbus_a_SOURCES += bf548_ezkit.c
endif

if ENABLE_BUS_BF561_EZKIT
libbus_a_SOURCES += bf561_ezkit.c
endif

if ENABLE_BUS_BSCOACH
libbus_a_SOURCES += bscoach.c
endif

if ENABLE_BUS_EJTAG
libbus_a_SOURCES += ejtag.c
endif

if ENABLE_BUS_EJTAG_DMA
libbus_a_SOURCES += ejtag_dma.c
endif

if ENABLE_BUS_FJMEM
libbus_a_SOURCES += fjmem.c
endif

if ENABLE_BUS_H7202
libbus_a_SOURCES += h7202.c
endif

if ENABLE_BUS_IXP425
libbus_a_SOURCES += ixp425.c
endif

if ENABLE_BUS_JOPCYC
libbus_a_SOURCES += jopcyc.c
endif

if ENABLE_BUS_LH7A400
libbus_a_SOURCES += lh7a400.c
endif

if ENABLE_BUS_MPC5200
libbus_a_SOURCES += mpc5200.c
endif

if ENABLE_BUS_MPC824X
libbus_a_SOURCES += mpc824x.c
endif

if ENABLE_BUS_PPC405EP
libbus_a_SOURCES += ppc405ep.c
endif

if ENABLE_BUS_PPC440GX_EBC8
libbus_a_SOURCES += ppc440gx_ebc8.c
endif

if ENABLE_BUS_PROTOTYPE
libbus_a_SOURCES += prototype.c
endif

if ENABLE_BUS_PXA2X0
libbus_a_SOURCES += pxa2x0.c
else
if ENABLE_BUS_PXA27X
libbus_a_SOURCES += pxa2x0.c
endif
endif

if ENABLE_BUS_S3C4510
libbus_a_SOURCES += s3c4510x.c
endif

if ENABLE_BUS_SA1110
libbus_a_SOURCES += sa1110.c
endif

if ENABLE_BUS_SH7727
libbus_a_SOURCES += sh7727.c
endif

if ENABLE_BUS_SH7750R
libbus_a_SOURCES += sh7750r.c
endif

if ENABLE_BUS_SH7751R
libbus_a_SOURCES += sh7751r.c
endif

if ENABLE_BUS_SHARC_21065L
libbus_a_SOURCES += sharc21065l.c
endif

if ENABLE_BUS_SLSUP3
libbus_a_SOURCES += slsup3.c
endif

if ENABLE_BUS_TX4925
libbus_a_SOURCES += tx4925.c
endif

if ENABLE_BUS_ZEFANT_XS3
libbus_a_SOURCES += zefant-xs3.c
endif
