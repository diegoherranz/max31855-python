max31855-python
===============

Python library to read Maxim's [MAX31855](http://www.maximintegrated.com/datasheet/index.mvp/id/7273) Cold-Junction Compensated Thermocouple-to-Digital Converter via SPI


Quick example
------------

    >>> import max31855
    >>> sensor = max31855.max31855('/dev/spidev1.0')
    >>> sensor.read_temperature()
    52.75  # Temperature in ºC
    
    

