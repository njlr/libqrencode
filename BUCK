include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'libqrencode',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('', '*.h'),
  ]),
  srcs = glob([
    '*.c',
  ]),
  compiler_flags = [
    '-DSTATIC_IN_RELEASE=static',
    '-DMAJOR_VERSION=3',
    '-DMINOR_VERSION=4',
    '-DMICRO_VERSION=4',
    '-DVERSION="3.4.4"',
  ],
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
