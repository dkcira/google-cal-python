# google-cal-python
google calendar with python

based on:
- https://karenapp.io/articles/2019/07/how-to-automate-google-calendar-with-python-using-the-calendar-api/
- https://github.com/karenapp/google-calendar-python-api


## instructions


```bash
pip3 install --upgrade \
 google-api-python-client \
 google-auth-httplib2 \
 google-auth-oauthlib
```

## scripts
- **cal_setup.py**: get auth token
- **list_calendars.py**: list calendars
- **list_events.py**: list events in the primary calendar
- **create_event.py**: create an event in the primary calendar at 10 AM the next day  in IST timezone. Also save the event ID for later use.
- **update_event.py**: update the event created in the primary calendar, from its original schedule of 10 AM to 9 AM, it also updates the summary and description.