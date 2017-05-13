project('vala-hello', ['vala', 'c'],
    version : '1.0.0',
    license: 'GPL-3.0'
)

executable(
    'vala-hello',
    'src/Main.vala',
    dependencies :[
        dependency('glib-2.0'),
        dependency('gobject-2.0'),
        dependency('gtk+-3.0'),
    ],
    install : true
)

install_data(
    'data/vala-hello.desktop',
    install_dir: '/usr/share/applications'
)
