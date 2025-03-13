```
python pagodo.py -d gob.mx -g dorks/files_containing_juicy_info.dorks -p 'http://78214235-zone-custom-region-US:3AR6suCi@aus.360s5.com:3600' -i 12 -x 20 -o result_gob_mx.json
python pagodo.py -d kueski.com -g dorks/files_containing_juicy_info.dorks -p 'http://78214235-zone-custom-region-US:3AR6suCi@aus.360s5.com:3600' -i 12 -x 20 -o result_kueski.json
```

```
nohup python pagodo.py -l -d kueski.com -g dorks/files_containing_juicy_info.dorks -p 'http://78214235-zone-custom-region-US:3AR6suCi@aus.360s5.com:3600' -i 12 -x 20 -o result_kueski.json 2>&1 &
nohup python pagodo.py -l -d gob.mx -g dorks/files_containing_juicy_info.dorks -p 'http://78214235-zone-custom-region-US:3AR6suCi@aus.360s5.com:3600' -i 12 -x 20 -o result_gob_mx.json 2>&1 &
```
