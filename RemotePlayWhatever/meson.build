
RPW_source = files(
   'RemotePlayWhatever.cpp',
	'RemotePlayWhatever.h',
	'SteamStuff.h',
	'SteamStuff.cpp',
	'RemoteApp.h',
	'RemoteApp.cpp',
	'RemotePlayInviteHandler.h',
	'RemotePlayInviteHandler.cpp'
)

RPW_bin = executable(
   'RemotePlayWhatever',
   RPW_source,
   dependencies: [
      dependency('wxWidgets', required: true),
      dependency('OpenSteamAPI', required: true)
      ],
   )

