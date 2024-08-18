from building import *
import os

cwd     = GetCurrentDir()
src     = []
group   = []
CPPPATH = [cwd]

src = Glob('*.cpp')

group = group + DefineGroup('qmc5883', src, depend = ['PKG_USING_QMC5883L'], CPPPATH = CPPPATH)

Return('group')