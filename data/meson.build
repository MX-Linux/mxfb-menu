fluxbox_files = [
	'menu-mx',
	'appearance',
	'out-of-sight',
	'settings'
	]
openbox_files = [
	'menu-mx.xml',
	]

install_data(fluxbox_files, 
	install_dir: join_paths(get_option('datadir'), 'mxfb-menu', 'fluxbox')
)

install_data(openbox_files, 
	install_dir: join_paths(get_option('datadir'), 'mxfb-menu', 'openbox')
)
install_data(openbox_files, 
	install_dir: join_paths(get_option('sysconfdir'), 'xdg', 'openbox')
)


