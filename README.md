# firehol-crosscheck

The `firehol-crosscheck` tool is a helpful bash-wrapper script to determine
which firehol references exist for a list of ip-addresses in a file.


## Usage
```
Usage: firehol-crosscheck <ipaddress-filename>
```


## Configuration
You MUST set the `firehol_blocklist_path` variable within the script first.


## Example
```
user@computer:~$ ./firehol-crosscheck ipv4-example-list.txt 
8.8.8.8 :: 6 :: coinbl_hosts,hphosts_ats,hphosts_emd,hphosts_fsa,hphosts_psh,packetmail_emerging_ips
1.1.1.1 :: 165 :: alienvault_reputation,bambenek_c2,bambenek_simda,bds_atif,bitcoin_blockchain_info_1d,bitcoin_blockchain_info_30d,bitcoin_blockchain_info_7d,bitcoin_nodes,bitcoin_nodes_1d,bitcoin_nodes_30d,bitcoin_nodes_7d,blocklist_de,blocklist_de_apache,blocklist_de_bruteforce,blocklist_de_imap,blocklist_de_mail,blocklist_de_sip,blocklist_de_ssh,blocklist_de_strongips,blocklist_net_ua,botscout,botscout_1d,botscout_30d,botscout_7d,botvrij_dst,bruteforceblocker,ciarmy,cleanmx_phishing,cleanmx_viruses,cleantalk,cleantalk_1d,cleantalk_30d,cleantalk_7d,cleantalk_new_30d,cleantalk_new_7d,cleantalk_updated,cleantalk_updated_1d,cleantalk_updated_30d,cleantalk_updated_7d,coinbl_hosts,coinbl_hosts_browser,coinbl_hosts_optional,coinbl_ips,cruzit_web_attacks,cta_cryptowall,cybercrime,dm_tor,dshield_top_1000,esentire_14072015_com,esentire_14072015q_com,esentire_22072014a_com,esentire_22072014b_com,esentire_22072014c_com,esentire_auth_update_ru,esentire_burmundisoul_ru,esentire_crazyerror_su,esentire_dagestanskiiviskis_ru,esentire_dorttlokolrt_com,esentire_downs1_ru,esentire_ebankoalalusys_ru,esentire_emptyarray_ru,esentire_fioartd_com,esentire_getarohirodrons_com,esentire_hasanhashsde_ru,esentire_inleet_ru,esentire_islamislamdi_ru,esentire_maddox1_ru,esentire_manning1_ru,esentire_misteryherson_ru,esentire_mysebstarion_ru,esentire_smartfoodsglutenfree_kz,esentire_venerologvasan93_ru,esentire_volaya_ru,et_botcc,et_compromised,et_tor,gpf_comics,greensnow,haley_ssh,hphosts_ats,hphosts_emd,hphosts_fsa,hphosts_grm,hphosts_hfs,hphosts_mmt,hphosts_pha,hphosts_psh,hphosts_wrz,ipblacklistcloud_recent_30d,ipblacklistcloud_recent_7d,ipblacklistcloud_top,lashback_ubl,malwaredomainlist,maxmind_proxy_fraud,myip,nixspam,normshield_all_attack,normshield_all_bruteforce,normshield_all_wannacry,normshield_high_attack,normshield_high_bruteforce,normshield_high_wannacry,nt_malware_dns,nt_malware_irc,nt_ssh_7d,nullsecure,packetmail,packetmail_ramnode,php_commenters_30d,php_dictionary_30d,php_dictionary_7d,php_harvesters,php_harvesters_1d,php_harvesters_30d,php_harvesters_7d,php_spammers_30d,php_spammers_7d,proxylists,proxylists_1d,proxylists_30d,proxylists_7d,proxyspy_1d,proxyspy_30d,proxyspy_7d,proxz_1d,proxz_30d,proxz_7d,sblam,snort_ipfilter,socks_proxy,socks_proxy_1d,socks_proxy_30d,socks_proxy_7d,sslproxies,sslproxies_1d,sslproxies_30d,sslproxies_7d,stopforumspam,stopforumspam_180d,stopforumspam_1d,stopforumspam_30d,stopforumspam_365d,stopforumspam_7d,stopforumspam_90d,taichung,talosintel_ipfilter,threatcrowd,tor_exits,tor_exits_1d,tor_exits_30d,tor_exits_7d,turris_greylist,urandomusto_dns,urandomusto_ftp,urandomusto_smb,urandomusto_ssh,urandomusto_unspecified,urlvir,uscert_hidden_cobra,xforce_bccs,xroxy,xroxy_1d,xroxy_30d,xroxy_7d,yoyo_adservers
9.9.9.9 :: 0
```


## Project
* [github.com/ndejong/firehol-crosscheck](https://github.com/ndejong/firehol-crosscheck)


## Authors
[Nicholas de Jong](https://nicholasdejong.com)


## License
BSD-2-Clause - see LICENSE file for full details.

