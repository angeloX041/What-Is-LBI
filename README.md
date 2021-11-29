# What-Is-LBI
Explaining what Is LBI
lbi - Lua bytecode interpreter

About:
	lbi is a bytecode interpreter for Lua written in Lua. It aims to allow
	the safe and fast emulation of Lua bytecode where using the standard C 
	facilities for this would be dangerous.

Usage:
	Call the function `load_bytecode` which is defined in ./src/lbi.lua
	It will act like the stdlib function `loadstring` except it only will
	accept Lua bytecode (i.e. strings beginning with '\27')

	Or the lbi interpreter can be used standalone by using the ./run.lua
	script. For example:

	$lua run.lua test_file.lua

License:
	lbi is distributed under the MIT license. See ./LICENSE
