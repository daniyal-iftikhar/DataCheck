# DataCheck
DataCheck is a lightweight monitor for local files and folders.

It does not replace backup software and does not store backups. It reads a source folder and its backup folder and reports on four properties: freshness (is the backup recent enough under a configured policy), completeness (is every monitored file present), integrity (do the contents match a trusted SHA-256 reference) and restore readiness (can a sample of files be copied to a separate location and verified). It combines these into a transparent Low, Medium or High risk rating and keeps a history of scans.
