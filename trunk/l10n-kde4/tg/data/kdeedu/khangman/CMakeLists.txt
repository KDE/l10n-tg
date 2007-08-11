FILE(GLOB datafiles *.kvtml)
install( FILES ${datafiles} DESTINATION  ${DATA_INSTALL_DIR}/khangman/data/tg )
install( FILES  tg.txt  DESTINATION ${DATA_INSTALL_DIR}/khangman )
