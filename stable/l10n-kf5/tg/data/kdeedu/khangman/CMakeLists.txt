FILE(GLOB datafiles *.kvtml)
install( FILES ${datafiles} DESTINATION  ${DATA_INSTALL_DIR}/apps/kvtml/tg )
install( FILES  tg.txt  DESTINATION ${DATA_INSTALL_DIR}/khangman )
