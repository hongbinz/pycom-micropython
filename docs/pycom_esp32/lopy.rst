LoPy
****

Pinout
======

The pinout of the module is available as a `PDF file <https://www.pycom.io/wp-content/uploads/2016/11/lopy_pinout.pdf>`_.


.. warning::

    DO NOT connect anything to Pins ``P5``, ``P6`` and ``P7``, as this pins are used byt the SPI bus that controls the LoRa radio. These pins should be treated as ``NC``. Wiring connections to these pins will cause incorrect behaviour of the LoRa radio.
