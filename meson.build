project('cunnywm', 'c',
    license : 'MIT', # AGPL soon
    version : '0.1')

freetype = dependency('freetype2')
x11 = dependency('X11')
fontcfg = dependency('fontconfig')

cunny_source = [
		   'src/cunnywm.c',
		   'src/util.c',
		   'src/drw.c',	
]
executable('cunnywm', cunny_source, dependencies : [x11, fontcfg, freetype], install : true, link_args : ['-lXft'])
install_man('src/cunnywm.1')
