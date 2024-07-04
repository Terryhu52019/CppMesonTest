project(
	'CppMesonTest',
	'cpp', version: '0.1.0',
	license: 'MIT',
	default_options: ['cpp_std=c++20'],
	meson_version: '>= 1.0.0'
)

boost_dep = dependency('boost')

executable(
	'main',
	'src/main.cpp',
	dependencies : boost_dep,
)
