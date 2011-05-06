``pyavm`` provides the AVM() class to retrieve AVM meta-data from an image file:

    >>> from pyavm import AVM

To use, simply create an instance of this class using the filename of the
image:

    >>> avm = AVM('myexample.jpg')

Then, you can view the contents by using

    >>> print avm

or

    >>> avm

Finally, the AVM meta-data can be accessed using the attribute notation:

    >>> avm.Spatial.Equinox
    'J2000'

    >>> avm.Publisher
    'Chandra X-ray Observatory'