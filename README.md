## TDS - IBM QRadar integration.
#### Installation
1. Upload extenstion .zip file with following command:
```
 /opt/qradar/bin/contentManagement.pl -a import -f [source_file]
```
After installation, the following objects will appear in QRadar:

- LSE - DemoTDSCustom_ext
- Log Source Type – Demo_TDS
- Log Sources : Demo_TDS(Disabled), TDS_F(enabled) with test ID (log source identifier).

2.  After adding this, configure QRadar IP and port in TDS, add a new device into Log Sources with right Log Source Identifier, or use TDS_F with right Log Source Identifier.

