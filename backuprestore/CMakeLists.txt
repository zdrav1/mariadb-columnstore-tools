IF(UNIX)
  INSTALL(FILES README.md DESTINATION ${BACKUP_RESTORE_DIR} )
  INSTALL(PROGRAMS columnstoreRestore columnstoreBackup DESTINATION ${BACKUP_RESTORE_DIR} )
ENDIF(UNIX)
