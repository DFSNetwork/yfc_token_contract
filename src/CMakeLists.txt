project(yfctoken)

set(EOSIO_WASM_OLD_BEHAVIOR "Off")
find_package(eosio.cdt)

add_contract( yfctoken yfctoken yfctoken.cpp )
target_include_directories( yfctoken PUBLIC ${CMAKE_SOURCE_DIR}/../include )
target_ricardian_directory( yfctoken ${CMAKE_SOURCE_DIR}/../ricardian )