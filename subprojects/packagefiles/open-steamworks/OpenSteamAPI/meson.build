OpenSteamAPI_source = files(
  'src/CCallbackMgr.cpp',
  'src/ClientWrap.cpp',
  'src/Interface_OSW.cpp'
)

OpenSteamAPI = static_library('OpenSteamAPI', 
  OpenSteamAPI_source,
  include_directories : inc)

OpenSteamAPI_dep = declare_dependency(include_directories : inc,
  link_with : OpenSteamAPI)
