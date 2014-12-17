You need an EnOcean USB dongle:

![EnOcean USB dongle](http://www.ehomeportal.de/shop/prodpic/BSC-EnOcean-USB-Stick-Smart-Connect-fuer-HomeMatic-CCU1-2-und-IP-Symcon-PM-0045_b_0.JPG)

Get one from [Farnell](http://uk.farnell.com/enocean/usb-300/usb-gateway-for-radio-868mhz/dp/2342011).

You need an EnOcean push button:

<img src="http://www.elektroland24.de/out/pictures/master/product/1/image_FMH4-RW_1.png" alt="Eltako push button" style="width:200px">

Get one from [Farnell](http://uk.farnell.com/enocean/ptm-210/module-switch-radio-tx-868mhz/dp/2134137) or Houm.io :)

    npm install
    ENOCEAN_DEV=/dev/cu.usbserial-FTXMJJM6 nodemon index.coffee
    [Click click]
    { enoceanAddress: '008baffe', event: 'keydown', key: '1' }
    { enoceanAddress: '008baffe', event: 'keyup', key: undefined }
    { enoceanAddress: '008baffe', event: 'keydown', key: '2' }
    { enoceanAddress: '008baffe', event: 'keyup', key: undefined }
    { enoceanAddress: '008baffe', event: 'keydown', key: '3' }
    { enoceanAddress: '008baffe', event: 'keyup', key: undefined }
    { enoceanAddress: '008baffe', event: 'keydown', key: '4' }
    { enoceanAddress: '008baffe', event: 'keyup', key: undefined }
    { enoceanAddress: '008baffe', event: 'keydown', key: '12' }
    { enoceanAddress: '008baffe', event: 'keyup', key: undefined }
    { enoceanAddress: '008baffe', event: 'keydown', key: '34' }
    { enoceanAddress: '008baffe', event: 'keyup', key: undefined }
