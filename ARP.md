# ARP Poisoning

### Commands

1. List 

```
ifconfig /all
```

2. Configure ARP entries

```
arp -a 
```

3. Adding a static entry

```
arp -s <ipAddr>  <physical addr>
```

4. Make sure we have static address

```
arp -a 
```

4. Deleting ARP cache entry 

```
arp -d <ipAddr>
```
