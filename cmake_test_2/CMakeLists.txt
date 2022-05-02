cmake_minimum_required(VERSION 3.22)
PROJECT( HELLO)
ADD_SUBDIRECTORY(src bin)
# install file
INSTALL( FILES COPYRIGHT README DESTINATION share/doc/cmake)

INSTALL( PROGRAMS runhello.sh DESTINATION bin )
INSTALL( DIRECTORY doc/  DESTINATION share/doc/cmake )


