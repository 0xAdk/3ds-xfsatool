cmake_minimum_required(VERSION 3.16)
project(xfsatool)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

add_executable(xfsatool
	"${CMAKE_SOURCE_DIR}/3ds-xfsatool/3ds-xfsatool.cpp"
	"${CMAKE_SOURCE_DIR}/3ds-xfsatool/xfsa.cpp"
	"${CMAKE_SOURCE_DIR}/3ds-xfsatool/fantasylife.cpp"
	"${CMAKE_SOURCE_DIR}/3ds-xfsatool/guild.cpp"
	"${CMAKE_SOURCE_DIR}/3ds-xfsatool/arc.cpp"
	"${CMAKE_SOURCE_DIR}/3ds-xfsatool/xpck.cpp"
	"${CMAKE_SOURCE_DIR}/3ds-xfsatool/utils.cpp"
	"${CMAKE_SOURCE_DIR}/3ds-xfsatool/compression.cpp"
	"${CMAKE_SOURCE_DIR}/3ds-xfsatool/cuecomp/lzss.cpp"
	"${CMAKE_SOURCE_DIR}/3ds-xfsatool/cuecomp/lzx.cpp"
	"${CMAKE_SOURCE_DIR}/3ds-xfsatool/cuecomp/huffman.cpp"
)
