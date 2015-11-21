====================================
Installation Guide
====================================

.. note::
	There are also some requirements to your server where Magento Shop is hosted (all these requirements are common for Magento but still we need to bring them up again):

- RAM memory over 512 Mbytes
- Free space on the server not less than the size of the backup
- Zlib support in PHP. You will need to configure PHP with zlib, but don't worry - most Magento servers have this feature on.
- Highly recommend you install on staging/test site before installing on your product/live site.


Downloading
-------------------
After purchasing extensions, you will receive an email that includes the link to download extensions or you can go to My Downloadable Products to them.


Preparation
-----------

- FTP clients (such as Filezilla, WinSCP, cuteFtp) to upload or copy all folders in the zip package to your Magento site root folder.
- Unzip the extension package.
- Disable Compilation: ``System > Tools > Compilation > Disabled``


Upload the extension
----------------
- Upload all files, folders in *step1* and *step2* into Magento Root directory.  
- Clean cache and Compilation

Clear cache in Magento Admin Go to System/Cache Management. Hit on Flush Magento Cache. 


.. tip:: 404 Access Denied
	Logout and Login again to avoid **Access denied 404 error** when you go to this product configuration.


Configuration
-------------

Go to System > Configuration > MageCheckout Extensions.

Testing
-------

Go to your store backend, front-end, make sure everything is ok. If there is any issue, please submit a ticket at http://support.magecheckout.com
