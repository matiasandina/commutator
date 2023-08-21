This folder contains the files to print and assemble a commutator for electrophysiology using a 16 channel Intan headstage.

There are two options for the electronic configuration:

* Intan's PCB Adapter
* Custom PCB

### Intan's PCB adapter

You can buy the PCB from intan.

### Custom PCB

Be aware that this involves soldering of the very small 12 PIN omnetics connector.

### Parts

Depending on your build, you might need the different parts outlined here. If you are also using the custom PCB, check the `Gerbers/` folder for the particular build.

| Part | URL | Part No. | Manufacturer | Support Material |
| --- | --- | --- | --- | --- |
| RHD SPI cable adapter board | [link](https://intantech.com/RHD_SPI_cables.html?tabSelect=RHDSPIadapter&yPos=0) | C3430 | Intan | [link](https://intantech.com/files/Intan_RHD2000_commutator.pdf) |
| Adafruit Slip Ring | [link](https://www.adafruit.com/product/1196)
 | 1196 | Adafruit |  |
| 12-pin Omnetics PZN-12 polarized nano connectors | [link](https://www.digikey.com/en/products/detail/omnetics/A79623-001/15784984) | A79623-001 | Omnetics | other options [here](https://www.digikey.com/en/ptm/o/omnetics/polarized-nano-pzn-connector-series) |

## Acknowledgements

This project was inspired by [his other project](https://github.com/LaubachLab/OECommutator). The designs were made by Michael Visconti. Design evaluation and animal troubleshooting was made by Matias Andina.