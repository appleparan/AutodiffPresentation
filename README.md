# AutodiffPresentation
Lab seminar

* How to run jupyter
    * Server side
```
/usr/bin/nohup jupyter notebook --port=8889 --no-browser &> jupyter.log 2>&1 &
```
    * Client side (OpenSSH)

```
ssh "remoteId"@"remoteIP" -p "remoteSSHPort" -NL 8157:localhost:8889 "remoteId"@"remoteIP"
```
    * clinet side (Putty)
* Putty, remoteId, remoteIP
* go to tunnel, add "localhost:8889" as destination

