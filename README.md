
<div align="center">
  <img src="https://blogs.cappriciosec.com/uploaders/behat-config-leaks-tool.png" alt="logo">
</div>


## Badges



[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
![PyPI - Version](https://img.shields.io/pypi/v/behat-config-leaks)
![PyPI - Downloads](https://img.shields.io/pypi/dm/behat-config-leaks)
![GitHub all releases](https://img.shields.io/github/downloads/Cappricio-Securities/behat-config-leaks/total)
<a href="https://github.com/Cappricio-Securities/behat-config-leaks/releases/"><img src="https://img.shields.io/github/release/Cappricio-Securities/behat-config-leaks"></a>![Profile_view](https://komarev.com/ghpvc/?username=Cappricio-Securities&label=Profile%20views&color=0e75b6&style=flat)
[![Follow Twitter](https://img.shields.io/twitter/follow/cappricio_sec?style=social)](https://twitter.com/cappricio_sec)
<p align="center">

<p align="center">







## License

[MIT](https://choosealicense.com/licenses/mit/)



## Installation 

1. Install Python3 and pip [Instructions Here](https://www.python.org/downloads/) (If you can't figure this out, you shouldn't really be using this)

   - Install via pip
     - ```bash
          pip install behat-config-leaks 
        ```
   - Run bellow command to check
     - `behat-config-leaks -h`

## Configurations 
2. We integrated with the Telegram API to receive instant notifications for vulnerability detection.
   
   - Telegram Notification
     - ```bash
          behat-config-leaks --chatid <YourTelegramChatID>
        ```
   - Open your telegram and search for [`@CappricioSecuritiesTools_bot`](https://web.telegram.org/k/#@CappricioSecuritiesTools_bot) and click start

## Usages 
3. This tool has multiple use cases.
   
   - To Check Single URL
     - ```bash
          behat-config-leaks -u http://example.com 
        ```
   - To Check List of URL 
      - ```bash
          behat-config-leaks -i urls.txt 
        ```
   - Save output into TXT file
      - ```bash
          behat-config-leaks -i urls.txt -o out.txt
        ```
   - Want to Learn about [`behat-config-leaks`](https://blogs.cappriciosec.com/blog/181/behat-config-leaks)? Then Type Below command
      - ```bash
          behat-config-leaks -b
        ```
     
<p align="center">
  <b>🚨 Disclaimer</b>
  
</p>
<p align="center">
<b>This tool is created for security bug identification and assistance; Cappricio Securities is not liable for any illegal use. 
  Use responsibly within legal and ethical boundaries. 🔐🛡️</b></p>


## Working PoC Video

[![asciicast](https://blogs.cappriciosec.com/uploaders/Screenshot%202024-06-03%20at%205.14.46%20PM.png)](https://asciinema.org/a/Lkg1WnjD1ElwvrmGazxSinBtl)




## Help menu

#### Get all items

```bash
👋 Hey Hacker
                                                                             v1.0
    __         __          __                         _____             __           __
   / /_  ___  / /_  ____ _/ /_      _________  ____  / __(_)___ _      / /__  ____ _/ /_______
  / __ \/ _ \/ __ \/ __ `/ __/_____/ ___/ __ \/ __ \/ /_/ / __ `/_____/ / _ \/ __ `/ //_/ ___/
 / /_/ /  __/ / / / /_/ / /_/_____/ /__/ /_/ / / / / __/ / /_/ /_____/ /  __/ /_/ / ,< (__  )
/_.___/\___/_/ /_/\__,_/\__/      \___/\____/_/ /_/_/ /_/\__, /     /_/\___/\__,_/_/|_/____/
                                                        /____/

                              Developed By https://cappriciosec.com
behat-config-leaks : Bug scanner for WebPentesters and Bugbounty Hunters 

$ behat-config-leaks [option]

Usage: behat-config-leaks [options]
```


| Argument | Type     | Description                | Examples |
| :-------- | :------- | :------------------------- | :------------------------- |
| `-u` | `--url` | URL to scan | behat-config-leaks -u https://target.com |
| `-i` | `--input` | filename Read input from txt  | behat-config-leaks -i target.txt | 
| `-o` | `--output` | filename Write output in txt file | behat-config-leaks -i target.txt -o output.txt |
| `-c` | `--chatid` | Creating Telegram Notification | behat-config-leaks --chatid yourid |
| `-b` | `--blog` | To Read about behat-config-leaks Bug | behat-config-leaks -b |
| `-h` | `--help` | Help Menu | behat-config-leaks -h |



## 🔗 Links
[![Website](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://cappriciosec.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karthikeyan--v/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/karthithehacker)



## Author

- [@karthithehacker](https://github.com/karthi-the-hacker/)



## Feedback

If you have any feedback, please reach out to us at contact@karthithehacker.com
