# cronlog

cronlog is lightweight script that helps to log cron jobs (or other scripts).

## USAGE
```bash
cronlog <jobname> /path/to/command [options...] 
```

## Outputs
Outputs are generated under ~/.cronlog/logs/

- cronlog.csv contains the latest results of the scripts
- each script will also have a .log file that contains its output.