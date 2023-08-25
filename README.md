# Shelly-nordPoolPrice

## Used for

This project is used to get electricity marketing prices from nord pool and manage shelly 1 plus device schedules to lowest hours.

Code takes hours between 0-23 and schedule shelly device to 3 cheapest hours. second code is to make a loop for the first code.

Code also have feature to send email notification right after shelly is scheduled. 


## how to use

Copy codes to your shelly repository and modify CONFIG object to match your device. you also need right endpoint (NordPoolPriceSchedule code object CONFIG.spotPriceUrl) to get nord pool prices, you can ask it arto.ohenoja@gmail.com. if you like to use email notification, then you need to set up azure or similar endpoint to get email notifications. Endpoints and passwords are hidden from the code. Run StartScheduling code to start find prices and get right loop for codes.

## support

arto.ohenoja@gmail.com
# Shelly-NordpoolPriceEmailAzure
