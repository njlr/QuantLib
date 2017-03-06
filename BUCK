include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'quantlib',
  header_namespace = 'ql',
  srcs = glob([
    'ql/**/*.cpp',
  ]),
  headers = subdir_glob([
    ('ql', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
