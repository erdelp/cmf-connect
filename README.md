Just a simple binary to help me connect my bluetooth headphones on 42 Paris machines, which has an awfully crowded bluetooth network.


Find your device MAC ADDRESS (by looking at it on your phone for example)

1. Change $MAC and $DEVICE_NAME

2. Add to 42 default path

```mkdir /home/$USER/bin/```

```mv cmf-connect /home/$USER/bin/```

3. Obviously

```chmod +x /home/$USER/bin/cmf-connect```

4. then *after putting your headphones/earbuds in pairing mode*

```cmf-connect```


PS: Why cmf-connect ? Just because thatś my earbud brand lol
