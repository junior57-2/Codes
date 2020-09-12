# Hi this codes help to generate
```
● StringSession
```
```
● TelegraphToken
```
```
● DriveToken
```
```
● GDriveRclone
```
```
● TokenPickle
```

-----

# **String Session** : String Session can be generated by https://repl.it/@Guru2509/GenerateStringSession or by running the following commands
```
pkg install python wget
wget https://raw.githubusercontent.com/guru-25/codes/master/generate_string_session.py
pip install pyrogram tgcrypto
python3 generate_string_session.py
```
(Use `python` if `python3` doesn't work) and then, paste your API KEY and API HASH there, and use the bot token/phone number and copy the token.

-----

# **Telegraph Token** : Telegraph token can be generated by https://repl.it/@Guru2509/GenerateTelegraphToken or by running the following commands
```
pkg install python wget
wget https://raw.githubusercontent.com/guru-25/codes/master/generate_telegraph_token.py
pip install telegraph
python3 generate_telegraph_token.py
```
(Use `python` if `python3` doesn't work) and give any name and copy the token.

-----

# **Drive Token** : Drive Token can be generated by https://repl.it/@Guru2509/GenerateDriveToken or by running the following commands
```
pkg install python wget
wget https://raw.githubusercontent.com/guru-25/codes/master/generate_drive_token.py
pip install oauth2client
python3 generate_drive_token.py
```
(Use `python` if `python3` doesn't work) and enter your client id, client secret, open the generated link, give authorize and paste the refresh token. Finally copy the generated token.

-----

# **Google Drive Rclone** : Rclone for Google Drive can be generated by running the following commands
```
pkg install rclone
rclone config
n
<any name>
13
<client id>
<client secret>
1
<folder id>
(skip)
n
y
<token>
y
27
y
q
```
(You have to give your own details for `name`, `client id`, `client secret` and `folder id` so that only I have used `< >`.
For `(skip)` just press the enter key.) and copy the token.

-----

# **Token Pickle** : Download `credentials.json` from https://console.developers.google.com and rename as `credentials.json` and move to Download directory. Also download [generate_token_pickle.py](https://raw.githubusercontent.com/Guru-25/Codes/master/generate_token_pickle.py) and move to `credentials.json` directory and run the following commands 
```
termux-setup-storage
cd /storage/emulated/0/Download
pkg install python
pip install google-api-python-client google-auth-httplib2 google-auth-oauthlib
python3 generate_token_pickle.py
```
(Use `python` if `python3` doesn't work) Vist the url and give authorization and enter the authorization code. After that check your Download location, `token.pickle` will be created.

-----
