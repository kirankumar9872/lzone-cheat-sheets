cat C:\Temp\json\temp.json | jq -cr '.[]' | sed 's/\\[tn]//g' > C:\Temp\json\temp1.json
