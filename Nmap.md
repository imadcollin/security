# Nmap

### Commands

The following syntax is used to scan a single IP:

```
nmap  127.1.10
```

2. Syntax for Scanning a Single Port

```
nmap -p 8080 127.1.10
   ```

3. Syntax for Scanning Range of Ports

```
nmap -p 80, 410 127.1.1.0
```

4. Syntax for Scanning 100 Most Common Ports

```
nmap -f 127.1.1.0
```

5. Syntax for Scanning a Host

```
nmap <host name> 
```

6. Syntax to Scan Using TCP SYN Scan

```
nmap -sS 127.1.1.0 
```

## Nmap Commands in Kali Linux

Nmap Command 1: nmap -T4 for Timing

```
nmap -T4 ipAddr
```

Nmap Command 2: nmap -sS for TCP SYN Scan

```
name -sS ipAddr
```

Nmap Command 3: nmap -sF for FIN Scan

```
nmap -sF ipAddr
```

Nmap Command 6: nmap -p for Port Scan

```
nmap -p21 ipAddr
```

## Other Commands

1. Ping ->  ```namp # ```
2. Scan the Most Popular Ports ->``` nmap -top.ports ipAddr ```