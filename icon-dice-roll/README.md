### Deployment to local tbears instance

* tbears deploy dice-roll -k keystores/keystore_test1.json -c config/tbears_cli_config.json
* tbears txresult txnhash 
* tbears call -c config/tbears_cli_config.json testcmdline/call.json
* tbears sendtx -k keystores/keystore_test1.json -c config/tbears_cli_config.json testcmdline/send_set_treasury.json
* tbears sendtx -k keystores/keystore_test1.json -c config/tbears_cli_config.json testcmdline/send_bet.json

### Deployment to testnet

note: use p@ssword1 as password
* tbears deploy -t tbears  dice-roll -f hxe9d75191906ccc604fc1e45a9f3c59fb856c215f -k keystores/keystore1.json -c config/tbears_cli_config_testnet.json

* tbears txresult txnhash -c config/tbears_cli_config_testnet.json

* Testnet tracker https://bicon.tracker.solidwallet.io/  put the score address 

* Iconex extension in chrome browser. Create a wallet and get wallet address
