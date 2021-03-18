import os
from building import *

src = []
group = []

cwd = GetCurrentDir()
src = Glob('*.c')
CPPPATH = [cwd]

group = DefineGroup('mlib', src, depend = [''], CPPPATH = CPPPATH)

Return('group')
