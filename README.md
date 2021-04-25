# P2P balance checker

P2P balance checker tool scrapes balance data of European P2P platforms and saves it in SQLite database.

### Supported P2P platforms:
- [Bondora](https://www.bondora.com/) - only platform with public API
- [Finbee](https://p2p.finbee.lt/)
- [Lenndy](https://lenndy.com)
- [Paskolų klubas (NEO finance)](https://www.paskoluklubas.lt/)
- [Robo.cash](https://robo.cash)
- [ViaInvest](https://viainvest.com/)
- [Viventor](https://www.viventor.com/)


### Run locally

1. Clone this repo:
	```bash
    git clone https://github.com/PauliusU/p2p_balance_checker.git
    ```
    
2. cd into project
    ```bash
    cd p2p-balance-ckecker
    ```
    
3. Install requirements:
	```bash
    pip install -r requirements.txt
    ```
     
4. Rename ".env_sample" to ".env" file and provide required logins
   
	```bash
    mv .env_sample .env
    ```
5. Download [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads) (WebDriver for Chrome) and place in the `/bin` folder
   

6. Run demo:
    
	```bash
    python demo.py
    ```