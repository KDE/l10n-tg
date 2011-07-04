FILE(GLOB datafiles *.kvtml)
install( FILES ${datafiles} DESTINATION  ${DATA_INSTALL_DIR}/kvtml/tg )
install( FILES  tg.txt  DESTINATION ${DATA_INSTALL_DIR}/khangman )
