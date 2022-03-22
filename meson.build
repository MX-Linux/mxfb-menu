project('mxfb-menu', version: '22.03.01mx', meson_version: '>=0.52.0')

i18n = import('i18n')
gettext_package = meson.project_name()
locale_dir = join_paths(get_option('prefix'), get_option('localedir'))
install_datadir = join_paths(get_option('prefix'), get_option('datadir'), 'mxfb-menu')
install_bindir = join_paths(get_option('prefix'), get_option('bindir'))

subdir('data')

#subdir('bin')
subdir('src')

subdir('po')

#subdir('i18n')
