# water_notification
import time
from plyer import notification
if __name__=="__main__":
    while(True):
        notification.notify(title="Please Drink Water now",
                            message="drink a glass of water now as your body requires water",
                            app_icon="",timeout=12)
        time.sleep(60*60)
           
