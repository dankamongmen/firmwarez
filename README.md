firmwarez
=========

System firmware verification and upgrade tool covering various hardware.

usage
=====

Run "firmwarez" with no options to list firmware on your system known to the
tool. "firmwarez download" will download all appropriate firmware, if possible.
"firmwarez upgrade" will apply all possible firmware updates.

supported hardware
==================

Company Model                               Type        Known PCI IDs
-------+-----------------------------------+-----------+-----------------------
LSI    |SAS 9211-8i HBA                    |SAS PCIe   |1000:0072
http://www.lsi.com/channel/products/storagecomponents/Pages/LSISAS9211-8i.aspx
-------+-----------------------------------+-----------+-----------------------

Applicable PCI device types:

 0106: Serial ATA controller
 0107: Serial Attached SCSI controller
