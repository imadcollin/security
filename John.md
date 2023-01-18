# John

### Commands

1. Install john

```
sudo apt install john
```

2. Cracking zip file

```
zip2john Test.zip
   ```

3. Create hash file

```
touch hash.txt
```

4. Attach hash

```
zip2john Test.zip > hash.txt
```

4. Run john

```
john --format=zip hash.txt
```

5. Classical password file

```
unshadow /etc/passwd /etc/shadow > passwordFile
```

6.Classical password file

```
johhn --single passworfile
```

### Modes:

1. Single Crack Mode 2.Incremental Mode 3.Hash Formats
