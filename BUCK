prebuilt_cxx_library(
  name = 'mpl', 
  header_only = True, 
  header_namespace = 'boost', 
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'), 
  ]), 
  licenses = [
    'LICENSE', 
  ], 
  deps = [
    'buckaroo.github.buckaroo-pm.boost-config//:config', 
    'buckaroo.github.buckaroo-pm.boost-preprocessor//:preprocessor', 
  ], 
  visibility = [
    'PUBLIC', 
  ], 
)
