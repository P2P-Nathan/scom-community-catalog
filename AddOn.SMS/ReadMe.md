### AddOn.SMS

This MP reads information about SCCM Maintenance Windows. If it finds an upcoming scheduled within the next 7 days then information is read in to SCOM. Then it populates “Collections” in SCOM with Windows Server Objects matching how it looks in SCCM. When the scheduled is run in SCCM the Collection objects and its member servers are put in to SCOM Maintenance Mode.