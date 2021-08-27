# Vaccine_slot_alert_Bot(co-win)
Cowin telegram bot which will send the information regarding vaccine availability within a district. So no need to check manually on cowin website about vaccine availability.

1) Understanding co-win API structure
2) Understanding how telegram bots and groups work

        2.1) create a bot, this can be done using botfather which is also a bot.
        2.2) create a group.
3) Now write the python script

        3.1) ping the co-win API & fetch data
        3.2) Extract the information we want
        3.3) push message to telegram group whenever availability is there.
        3.4) Run the script every 1 hour.
4) Added more parameters date, vaccine_type(free or paid), vaccine_name.
5) Too many messages: sending message at a centre level, not session level.
        5.1) 429 --rate limit exceed, 100 API calls per minute.
6) Now run periodically...         
                    
