from building import *

cwd     = GetCurrentDir()
src     = Glob('*.c')
CPPPATH = [cwd]

group = DefineGroup('WebClient', src, depend = ['RT_USING_LWIP'], CPPPATH = CPPPATH)

Return('group')
