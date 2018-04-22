This is my packaged version of the [EZ-USB FX3 Software Development Kit for Linux](http://www.cypress.com/documentation/software-and-drivers/ez-usb-fx3-software-development-kit).

I only included libcyusb in here, but in [releases](https://github.com/hmaarrfk/libcyusb/releases/tag/v1.0.5),
you should find the full 1.0.5 version of the software that has been modified to have an LGPL license.

# Build from source

```
mkdir build
cd build
cmake ..
make
```

# Fedora
Find it on copr


To obtain the LGPL v2.1 license, I had to send a request to the Cypress Support
team and press them a little bit for an "early" release of their SDK.

Email excerpt:

> An Interaction has been added to the case#00416794 by Abhinav Garg.
>
> -------------------------------------------------------------------------------------
> Hello Mark,
>
> PFA libcyusb_linux with the updated LGPL license. There are a few other updates (to the GUI) which are documented in the user guide.
>
> Hope this will help !!
>
> Thanks & Regards
>
> Abhinav
>
> -------------------------------------------------------------------------------------
>
> You may view your case here:
> https://www.cypress.com/mycases/5001a00000ZVQrN
>
> Alternately, posting a response via reply e-mail will append your comments directly to the case.
>
> To view or download attachments, please access the case on our support website by clicking on the link provided above.
>
> Thank You.
>
> ref:_00D1a000000YMuW._5001a00000ZVQrN:ref
>
