# Poison-Hunter: Characterizing Ethereum Address Poisoning Attack (ACM CCS'24)
Dataset of benign addresses and sample phishing addresses involved in the Ethereum address poisoning attacks.

## Ground-truth dataset we used to evaluate Poison-Hunter
The `benign_addresses_on_etherscan.txt` contains 1154 popular Ethereum addresses assigned with benign labels on Etherscan. `phishing_address_groundtruth.txt` contains 5890 phishing addresses labeled by both Etherscan and forta. `phishing_address_we_detected_TP.txt` contains the 5729 phishing addresses our ``Poison-Hunter`` detected from the 5890 labeled phishing addresses.

## Sample phishing transfers and addresses
The `phishing_transfers_sample.csv` contains 150 samples of phishing addresses, the targeted victim addresses, as well as the phishing transfers and targeted benign transfers. Due to ethical concerns and the limited file size, we cannot upload the entire set of phishing addresses we have detected. If you need to obtain the rest of the phishing transfers and addresses presented in our paper, please contact us. 

 
#### To cite our work:

```
@inproceedings{guan2024characterizing,
  title={Characterizing Ethereum Address Poisoning Attack},
  author={Guan, Shixuan and Li, Kai},
  booktitle={Proceedings of the 2024 on ACM SIGSAC Conference on Computer and Communications Security},
  pages={986--1000},
  year={2024}
}
```
