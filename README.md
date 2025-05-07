### Prerequisite: install requests
```
python -m pip install requests
```
## 1. GET Bitbucket code
Replace {client_id} with the Consumer Key then run in the browser. You should get Bitbucket code
```
https://bitbucket.org/site/oauth2/authorize?client_id={client_id}&response_type=code

https://bitbucket.org/site/oauth2/authorize?client_id=3E3C7Pv5CmtpuGZHQA&response_type=code

```

## 2. Execute
```
cd /evizi/cwconnect/release-script
python releaseScript.py
```
## 3. Copy result.csv to google sheet