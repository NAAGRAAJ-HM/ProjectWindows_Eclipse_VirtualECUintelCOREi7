default_target: all
.PHONY : default_target

.NOTPARALLEL:

.SUFFIXES:

% : %,v

% : RCS/%

% : RCS/%,v

% : SCCS/s.%

% : s.%

.SUFFIXES: .hpux_make_needs_suffix_list

CC                   = g++
CXX_DEFINES          = 
CMAKE_BINARY_DIR     = .
CMAKE_SOURCE_DIR     = .
CXX_FLAGS            = -g -std=c++2a -Wall -Werror -Wextra -pedantic -Wuninitialized -std=gnu++20
LDD_FLAGS            = $(CXX_FLAGS)
CXX_SOURCES          = $(CMAKE_SOURCE_DIR)/source/SmbLnk2_CfgGen/CfgGen.cpp                 \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Const/Const.cpp                   \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_CanIf/CanIf.cpp                   \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_CanNm/CanNm.cpp                   \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_CanSm/CanSm.cpp                   \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_CanTp/CanTp.cpp                   \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_CryIf/CryIf.cpp                   \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Ea/Ea.cpp                         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_EthIf/EthIf.cpp                   \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Fee/Fee.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_FrIf/FrIf.cpp                     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_FrTp/FrTp.cpp                     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_J1939Tp/J1939Tp.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_LinIf/LinIf.cpp                   \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_LinTp/LinTp.cpp                   \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_MemIf/MemIf.cpp                   \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_WdgIf/WdgIf.cpp                   \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Adc/Adc.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Can/Can.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Cry/Cry.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Dio/Dio.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Eep/Eep.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Eth/Eth.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Fls/Fls.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Fr/Fr.cpp                         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Gpt/Gpt.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Icu/Icu.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Lin/Lin.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Mcu/Mcu.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Ocu/Ocu.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Port/Port.cpp                     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Pwm/Pwm.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Spi/Spi.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Wdg/Wdg.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_BswM/BswM.cpp                     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Com/Com.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_ComM/ComM.cpp                     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Csm/Csm.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Dcm/Dcm.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Dem/Dem.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Det/Det.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Dlt/Dlt.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuM/EcuM.cpp                     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_FiM/FiM.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_FrNm/FrNm.cpp                     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_IpduM/IpduM.cpp                   \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Nm/Nm.cpp                         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_NvM/NvM.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Os/Os.cpp                         \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_PduR/PduR.cpp                     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_SchM/SchM.cpp                     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_SecOC/SecOC.cpp                   \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_SokFm/SokFm.cpp                   \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_StartUp/StartUp.cpp               \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_StbM/StbM.cpp                     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Vkms/Vkms.cpp                     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_WdgM/WdgM.cpp                     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_Rte/Rte.cpp                       \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_SwcServiceEcuM/SwcServiceEcuM.cpp \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_SwcServiceOs/SwcServiceOs.cpp     \
                       $(CMAKE_SOURCE_DIR)/source/SmbLnk2_SwcApplFoc/SwcApplFoc.cpp         \

CXX_OBJECTS          = $(CMAKE_BINARY_DIR)/CfgGen.o                            \
                       $(CMAKE_BINARY_DIR)/Const.o                             \
                       $(CMAKE_BINARY_DIR)/CanIf.o                             \
                       $(CMAKE_BINARY_DIR)/CanNm.o                             \
                       $(CMAKE_BINARY_DIR)/CanSm.o                             \
                       $(CMAKE_BINARY_DIR)/CanTp.o                             \
                       $(CMAKE_BINARY_DIR)/CryIf.o                             \
                       $(CMAKE_BINARY_DIR)/Ea.o                                \
                       $(CMAKE_BINARY_DIR)/EthIf.o                             \
                       $(CMAKE_BINARY_DIR)/Fee.o                               \
                       $(CMAKE_BINARY_DIR)/FrIf.o                              \
                       $(CMAKE_BINARY_DIR)/FrTp.o                              \
                       $(CMAKE_BINARY_DIR)/J1939Tp.o                           \
                       $(CMAKE_BINARY_DIR)/LinIf.o                             \
                       $(CMAKE_BINARY_DIR)/LinTp.o                             \
                       $(CMAKE_BINARY_DIR)/MemIf.o                             \
                       $(CMAKE_BINARY_DIR)/WdgIf.o                             \
                       $(CMAKE_BINARY_DIR)/Adc.o                               \
                       $(CMAKE_BINARY_DIR)/Can.o                               \
                       $(CMAKE_BINARY_DIR)/Cry.o                               \
                       $(CMAKE_BINARY_DIR)/Dio.o                               \
                       $(CMAKE_BINARY_DIR)/Eep.o                               \
                       $(CMAKE_BINARY_DIR)/Eth.o                               \
                       $(CMAKE_BINARY_DIR)/Fls.o                               \
                       $(CMAKE_BINARY_DIR)/Fr.o                                \
                       $(CMAKE_BINARY_DIR)/Gpt.o                               \
                       $(CMAKE_BINARY_DIR)/Icu.o                               \
                       $(CMAKE_BINARY_DIR)/Lin.o                               \
                       $(CMAKE_BINARY_DIR)/Mcu.o                               \
                       $(CMAKE_BINARY_DIR)/Ocu.o                               \
                       $(CMAKE_BINARY_DIR)/Port.o                              \
                       $(CMAKE_BINARY_DIR)/Pwm.o                               \
                       $(CMAKE_BINARY_DIR)/Spi.o                               \
                       $(CMAKE_BINARY_DIR)/Wdg.o                               \
                       $(CMAKE_BINARY_DIR)/BswM.o                              \
                       $(CMAKE_BINARY_DIR)/Com.o                               \
                       $(CMAKE_BINARY_DIR)/ComM.o                              \
                       $(CMAKE_BINARY_DIR)/Csm.o                               \
                       $(CMAKE_BINARY_DIR)/Dcm.o                               \
                       $(CMAKE_BINARY_DIR)/Dem.o                               \
                       $(CMAKE_BINARY_DIR)/Det.o                               \
                       $(CMAKE_BINARY_DIR)/Dlt.o                               \
                       $(CMAKE_BINARY_DIR)/EcuM.o                              \
                       $(CMAKE_BINARY_DIR)/FiM.o                               \
                       $(CMAKE_BINARY_DIR)/FrNm.o                              \
                       $(CMAKE_BINARY_DIR)/IpduM.o                             \
                       $(CMAKE_BINARY_DIR)/Nm.o                                \
                       $(CMAKE_BINARY_DIR)/NvM.o                               \
                       $(CMAKE_BINARY_DIR)/Os.o                                \
                       $(CMAKE_BINARY_DIR)/PduR.o                              \
                       $(CMAKE_BINARY_DIR)/SchM.o                              \
                       $(CMAKE_BINARY_DIR)/SecOC.o                             \
                       $(CMAKE_BINARY_DIR)/SokFm.o                             \
                       $(CMAKE_BINARY_DIR)/StartUp.o                           \
                       $(CMAKE_BINARY_DIR)/StbM.o                              \
                       $(CMAKE_BINARY_DIR)/Vkms.o                              \
                       $(CMAKE_BINARY_DIR)/WdgM.o                              \
                       $(CMAKE_BINARY_DIR)/Rte.o                               \
                       $(CMAKE_BINARY_DIR)/SwcServiceEcuM.o                    \
                       $(CMAKE_BINARY_DIR)/SwcServiceOs.o                      \
                       $(CMAKE_BINARY_DIR)/SwcApplFoc.o                        \

CXX_INCLUDES         = -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_common             \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Compiler           \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_CfgGen             \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Const              \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_CanIf              \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_CanNm              \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_CanSm              \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_CanTp              \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_CryIf              \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Ea                 \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_EthIf              \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Fee                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_FrIf               \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_FrTp               \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_J1939Tp            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_LinIf              \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_LinTp              \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_MemIf              \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_WdgIf              \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Adc                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Can                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Cry                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Dio                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Eep                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Eth                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Fls                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Fr                 \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Gpt                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Icu                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Lin                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Mcu                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Ocu                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Port               \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Pwm                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Spi                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Wdg                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_BswM               \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Com                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_ComM               \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Csm                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Dcm                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Dem                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Det                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Dlt                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_EcuM               \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_FiM                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_FrNm               \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_IpduM              \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Nm                 \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_NvM                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Os                 \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_PduR               \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_SchM               \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_SecOC              \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_SokFm              \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_StartUp            \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_StbM               \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Vkms               \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_WdgM               \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_Rte                \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_SwcServiceEcuM     \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_SwcServiceOs       \
                       -I$(CMAKE_SOURCE_DIR)/source/SmbLnk2_SwcApplFoc         \

CXX_OBJECTS1 = $(subst .cpp,.o,$(CXX_SOURCES))

all: Windows10Home_Eclipse2022-06_PEAQc150_VirtualECU_intelCOREi7.exe
.PHONY : all

clean:
	rm $(CMAKE_BINARY_DIR)/Windows10Home_Eclipse2022-06_PEAQc150_VirtualECU_intelCOREi7.exe  $(CXX_OBJECTS)
.PHONY : clean

%.o: %.cpp
	$(CC) $(CXX_FLAGS) $(CXX_INCLUDES) -c $<

Windows10Home_Eclipse2022-06_PEAQc150_VirtualECU_intelCOREi7.exe: $(CXX_OBJECTS1)
	$(CC) $(LDD_FLAGS) -o $(CMAKE_BINARY_DIR)/Windows10Home_Eclipse2022-06_PEAQc150_VirtualECU_intelCOREi7.exe $(CXX_OBJECTS)
