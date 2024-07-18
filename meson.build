project(
	'CppMesonTest',
	'cpp', version: '0.1.0',
	license: 'MIT',
	default_options: ['cpp_std=c++20'],
	meson_version: '>= 1.0.0'
)

boost_dep = dependency('boost')
incdir = include_directories('include')

executable(
	'main',
	'src/main.cpp',
	dependencies : boost_dep,
	include_directories : incdir
)
