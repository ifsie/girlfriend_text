# Reminds your best bud to kill their self
Send text to your punching bag in the morning

## 1. Configure your settings in `utils.py`.
```py
phone_number = "+15555555555"
# enter the target phone number inside quotation marks. use the format "+15555555555"
message = ["kill yourself you fat peice of shit, honestly noone fucking loves you. your dog doesnt even let you pet him you're and utter disappointment to everyone around you", "fucking kill your self already we've been waiting for about a year now and it's making us suffer that you fucking exist", "kys"]
# just make sure the message is inside quotation marks. An example is "die die die die die"
scheduled_time = "08:00"
# make sure the hour has 2 digits (24-hour standard).
```

Note: If you want to send a message everyday at 8:45 AM, you will need to set `scheduled_time = "08:45"` in `utils.py`

## 2. Install requirements
```bash
python3 -m pip install -r requirements.txt
```

## 3. Run the script
```bash
python3 main.py
```
Note: If you want run in background

```bash
python3 main.py > pid.txt 2>&1 & 
```
*Jobs can be accessed with the `jobs` command. jobs will show you the running jobs, and number them. You could then talk about the jobs using a `%` followed by the number like `kill %1` or so.*

Don't give me credit for this, it's not mine
