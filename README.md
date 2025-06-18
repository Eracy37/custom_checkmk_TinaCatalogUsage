## custom_checkmk_TinaCatalogUsage
Script for usage check Tina catalog for checkmk (core nagios)

### Use
For use on checkmk put the script in ```/usr/var/lib/check_mk_agent/local```
You can find the api url and token on tina's webui. 

Modify configuration elements on the script (THRESHOLD are in percent):
```bash
API_URL="https://XXX"
TOKEN="XXX"
WARNING_THRESHOLD=XX
CRITICAL_THRESHOLD=XX
```




