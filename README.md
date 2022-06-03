# newACTS solution: 

# Created: 20201017

 # 1. qcustomplot.cpp： warning C4996:  Debug  

'std::copy_backward::_Unchecked_iterators::_Deprecate': Call to 'std::copy_backward' with parameters that may be unsafe - . To disable this warning, use -D_SCL_SECURE_NO_WARNINGS. 
https://stackoverflow.com/questions/33057834/how-to-disable-a-warning-in-visual-studio-2015-for-c

Property Pages -> C/C++ -> Advanced -> Disable Specific Warnings: (Ignore specific warnings -> 4996.)

4996;%(DisableSpecificWarnings)


# 2. Debug info output window

Property Pages -> Linker -> System -> SubSystem -> Console(/SUBSYSTEM:CONSOLOE)
