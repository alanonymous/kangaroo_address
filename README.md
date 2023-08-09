# kangaroo_address
bitcrack_keyhunt_Kangaroo

This program is really only intended for the BTC Challenge

tested on Windows 10 and Windows 11 on RTX 4090 cards, RTX 20xx cards

# All operating parameters are inside the use.txt file

# RUN

```
C:\>kangaroo_address.exe -t 0 -b 43 -gpu -g 256,256 -s 1PiFuqGpG8yGM5v6rNHWS3TjsG6awgEGA1
kangaroo_address v4.1
 Search For: 1PiFuqGpG8yGM5v6rNHWS3TjsG6awgEGA1 [Compressed]
 Started on: Wed Aug 9 02:08:55 2023
  Beg Range: 40000000000 (43 bit)
  End Range: 7ffffffffff (43 bit)
  Rng Width: 3FFFFFFFFFF (42 bit)
CPU Threads: 0
GPU: GPU #0 NVIDIA GeForce RTX 4090
 
 [00:00:01:16 Run Time][Total 2071.02 MK/s][GPU 2071.02 MK/s][Keys 7,620,557,143,166][Found 0][Rekeys: 1]


PubAddress: 1PiFuqGpG8yGM5v6rNHWS3TjsG6awgEGA1
Priv (WIF): p2pkh: KwDiBf89QgGbjEhKnhXJuH7LrciVrZi3qYjgdB23bP5LsYN8Krv7
Priv (HEX): 6BD3B27C591 (43 bit)
```

# usage for puzzle 66 and 67 and 68 and 69...

```
C:\>kangaroo_address.exe -t 0 -b 66 -gpu -g 256,256 -s 13zb1hQbWVsc2S7ZTZnP2G4undNNpdh5so
kangaroo_address v4.1
 Search For: 13zb1hQbWVsc2S7ZTZnP2G4undNNpdh5so [Compressed]
 Started on: Wed Aug 9 03:54:14 2023
  Beg Range: 20000000000000000 (66 bit)
  End Range: 3FFFFFFFFFFFFFFFF (66 bit)
  Rng Width: 1FFFFFFFFFFFFFFFF (65 bit)
CPU Threads: 0
GPU: GPU #0 NVIDIA GeForce RTX 4090

[00:00:23:08 Run Time][Total 2068.89 MK/s][GPU 2068.89 MK/s][Keys 117,846,349,102,375][Found 0][Rekeys: 0]

```
