# QuarksPwDump-off-line
 - -k    --get-system-key
 - -dhl  --dump-hash-local
 - -dhdc --dump-hash-domain-cached
 - -dhd  --dump-hash-domain (NTDS_FILE must be specified)
 - -db   --dump-bitlocker (NTDS_FILE must be specified)
 - -sf   --system-file FILE
 - -sk   --system-key KEY
 - -nt   --ntds-file FILE
 - -hist --with-history (optional)
 - -t    --output-type JOHN/LC (optional, if no=>JOHN)
 - -o    --output FILE (optional, if no=>stdout)
**New parameter added**
 - -k    --get-system-key
 - -sf   --system-file FILE
 - -sk   --system-key KEY

**Example:**

 1. QuarksPwDump.exe -k
 2. QuarksPwDump.exe -dhd -nt NTDS_saved.dit -sf system.hive -o hash.txt
 3. QuarksPwDump.exe -dhd -nt NTDS_saved.dit -sk 33A97A6A092FCB44B0598Axxxxxxxxx  -o hash.txt

