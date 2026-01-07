# Security Remediation Preferences

## SQL Injection

When executing queries against the Servers table, only the hostname and status columns should be allowed for sorting the results.

## Path Traversal

Make sure to verify the filename itself is safe vefore appending it to a path or file handle.  For zip files, use the following filename allowlist:
- test1.zip
- test2.zip
- test3.zip