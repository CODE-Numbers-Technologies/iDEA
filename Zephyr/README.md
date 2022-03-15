<div align="center">
    <h1>IDEA: Zephyr</h1>
    <q>Shall we do something of our own?</q>
</div>


The zephyr project is an encrypted, open source messenger written for Linux, Windows, Mac.
We think it will be some kind of analog for Telegram. We also plan to integrate Telegram with zephyr.
Zephyr-cli is a console-oriented client.

Our plans for this project are:
- Messenger with encryption;
- Simple and beautiful;
- Can change language;
- Can change themes;
- Voice messages;
- Text messages;
- Open Source;
- Audio/Video calls in hight resolution and AI;
- AI Assistant (IDEA:Gorgona);
- Achivments;


## API Templates
#### Authorization and registration
```
POST:{
    'Token': sha256(reversed_salt + login + password + salt)
    }
```

## User Database Example
#### User:
Username | EMail | Ename | Epass | About 
---|---|---|---|---
Twelve | twelve@gmail.com | 534jknfwelj452342354dasd | sdf34kjhfg34 | GoodMan

## Encryption
REVERSED_SALT + LOGIN + PASSWORD + SALT = SHA256
 

