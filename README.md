# ANON UTXO SNAPSHOT
**DATE: 09.10.2018 TIME: 11:00 PM (EST)**

Note: you don't have to download the utxo snapshot files in order to run a full node. It is OPTIONAL.

These are the files that were used to create airdropped blocks.  
If you want to validate blocks that are in the airdropped region (blocks 4 - 16,740) against these file records, this is how you do it:
1. Download and unzip it (location does't matter).
2. Add to your anon.conf file the following:
```
utxo-path="full path to your unziped folder"
```

3. Restart your node with -reindex.

4. During the -reindex Anon node will perform blocks validation against these file records. It will not accept any blocks that do not pass the validation. 

Note: This can take up to 8-10 hours.

**Details:**

FINAL ANON MAINNET SNAPSHOT
  ```
     Bitcoin funds        [00001 - 09892]  - 9892 files (5000 utxo per file)
     Zclassic t-funds     [09893 - 10131]  -  239 files (5000 utxo per file)
     Zclassic z-funds     [10132 - 16737]  - 6606 files (50 joinsplits per file) 
  ```
[DOWNLOAD](https://assets.anonfork.io/anon-utxo-snapshot.zip)

Raw link: 
https://assets.anonfork.io/anon-utxo-snapshot.zip


```
BITCOIN (upto block 540,870)
##########################################
Total T written: 	49455212
##########################################
Total T-files written: 	9892
utxo-00001.bin - utxo-09892.bin
Total transactions written: 	49455212
Total files created: 	9892
##########################################
```

```
ZCL-T (upto block 382,307)
##########################################
Total T written: 	1191185
##########################################
Total T-files written: 	239
utxo-09893.bin - utxo-10131.bin
Total transactions written: 	1191185
Total files created: 	239
##########################################
```


```
ZCL-Z (upto block 382,307)
##########################################
Found duplicates: 	0
Total Z written: 	330005
Total Z-files written: 	6606
utxo-10132.bin - utxo-16737.bin
Total transactions written: 	330005
Total files created: 	6606
##########################################
```

