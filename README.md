# Mass SQLi Scanner

### Descrição:
Script criado para identificar sites vulneráveis a falha SQL Injection

### About:

- Coder: v4p0r
- Team: Yunkers Crew
- Twitter: 0x777null
- Skype: drx.priv

### Como usar:

```
$ perl SQLi.pl

*      ___
     /`   `'.          *        *       *       *       *
    /   _..---;  *
    |  /__..._/  .--.-.    *             *                    *
 *  |.'  e e | ___\_|/____
   (_)'--.o.--|    | |    |  Mass SQLi Scanner      *
  .-( `-' = `-|____| |____|  Coder: v4p0r       *
 /  (         |____   ____|  Date: 01 NOV 20         *          *
 |   (        |_   | |  __|  Gretz: YC - HighTech - We BoyZ and All Friends
 |    '-.--';/'/__ | | (  `|   *
 |      '.   \    )"";--`\ /               *           *
 \        ;   |--'    `;.-'       *               *                 *
 |`-.__ ..-'--'`;..--'`
   *         *         *             *         *          *
# Team: Yunkers Crew
# Twitter: 0x777null
# Skype: drx.priv

# Usage: perl SQLi.pl --help

```

### Help script:
```
$ perl SQLi.pl --help

*      ___
     /`   `'.          *        *       *       *       *
    /   _..---;  *
    |  /__..._/  .--.-.    *             *                    *
 *  |.'  e e | ___\_|/____
   (_)'--.o.--|    | |    |  Mass SQLi Scanner      *
  .-( `-' = `-|____| |____|  Coder: v4p0r       *
 /  (         |____   ____|  Date: 01 NOV 20         *          *
 |   (        |_   | |  __|  Gretz: YC - HighTech - We BoyZ and All Friends
 |    '-.--';/'/__ | | (  `|   *
 |      '.   \    )"";--`\ /               *           *
 \        ;   |--'    `;.-'       *               *                 *
 |`-.__ ..-'--'`;..--'`
   *         *         *             *         *          *

 Usage: SQLi.pl [comando]

 [+] Comandos:

  --list    [Checa uma lista de sites]
  --site    [Testa um unico site]
  --payload [Seleciona um payload desejado]
            [Default > %27 <]
  --save    [Onde os sites vuln serao salvos]
            [Default > save_sqli.txt]

[!] Exemplos:

  perl SQLi.pl --list vulns.txt --save sqli.txt
  perl SQLi.pl --list vulns.txt --payload ' --save sqli.txt
  perl SQLi.pl --site localhost/index.php?id=1

```

### Script Print:

- ![image](https://image.prntscr.com/image/XZcl2Bw5TH_QYoldfj5u3A.png)
