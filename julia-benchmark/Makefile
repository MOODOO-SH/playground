FC=gfortran

all: perf.c.bin perf.f90.bin

perf.c.bin: perf.c
	$(CC) -std=c99 -O3 $< -o $@ 

perf.f90.bin: perf.f90
	$(FC) $(FFLAGS) -O3 $< -o $@
	rm *.mod

