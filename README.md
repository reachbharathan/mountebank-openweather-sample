# mountebank-openweather-sample

### To Install mountebank
``` npm install -g mountebank ```

### To start mountebank
``` mb --configfile templates/imposters.ejs --allowInjection ```

### Test the proxy
``` http://localhost:5555/data/2.5/weather?id={CITY_CODE}&APPID={APP_ID} ```
