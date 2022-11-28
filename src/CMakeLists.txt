add_executable(lego-address-dumper

)

if(MSVC)
  target_compile_options(lego-address-dumper /W4 /WX)
else()
  target_compile_options(lego-address-dumper -Wall -Wextra -Wpedantic -Werror)
endif()