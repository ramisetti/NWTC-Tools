# NWTC-Tools
This repo contains some tools from NWTC-NREL useful to run with FAST/OpenFAST software. The makefiles for IECWind and TurbSim are slightly modified to make them work on a linux machine with gfortran version above 5.0

# Compiling TurbSim
cd TurbSim/compiling
export FC=gfortran; export F95=gfortran;
make clean
# the below command will generate TurbSim_glin64 in bin directory in TurbSim
make all

# Compiling IECWind
cd IECWind/compiling
export FC=gfortran; export F95=gfortran;
make clean
# the below command will generate IECWind_glin64 in bin directory in IECWind
make all 
