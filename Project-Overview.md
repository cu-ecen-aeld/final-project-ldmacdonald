# Overview
![Flow Diagram](./Flow_Diagram.JPG)

The project is a Proof of Concept for a traceable vending platform integrating with an external identity provider and other relevant APIs to ensure proper tracking and stockkeeping functionalities while still supporting disconnected operations.
Would also have applications in governance relevant industries such as medical supply dispensing.

# Target Build System
This project will be built leveraging Buildroot

# Hardware Platform
Raspberry Pi 3 Model B Plus Rev 1.3

Stretch Goal: Raspberry Pi Zero 2 W SC1176 [link](https://www.digikey.com/en/products/detail/raspberry-pi/SC1176/15298147?gclsrc=aw.ds&&utm_adgroup=&utm_source=google&utm_medium=cpc&utm_campaign=PMax%20Shopping_Product_Medium%20ROAS%20Categories&utm_term=&utm_content=&utm_id=go_cmp-20223376311_adg-_ad-__dev-c_ext-_prd-15298147_sig-CjwKCAjwp8--BhBREiwAj7og18MdhbM29LcZwpWjNTiTXZhPmdGaFFPicahz__aX0MbnNa4ISJUJWRoCrpYQAvD_BwE&gad_source=1&gclid=CjwKCAjwp8--BhBREiwAj7og18MdhbM29LcZwpWjNTiTXZhPmdGaFFPicahz__aX0MbnNa4ISJUJWRoCrpYQAvD_BwE&gclsrc=aw.ds)

Barcode Scanner: SEN-18088 [link](https://www.digikey.com/en/products/detail/sparkfun-electronics/SEN-18088/14322716?gclsrc=aw.ds&&utm_adgroup=&utm_source=google&utm_medium=cpc&utm_campaign=PMax%20Shopping_Product_Low%20ROAS%20Categories&utm_term=&utm_content=&utm_id=go_cmp-20243063506_adg-_ad-__dev-c_ext-_prd-14322716_sig-CjwKCAjwp8--BhBREiwAj7og15LEvOnd4pqCTEfCy5iSgRbU25ds0fdi55EgCMySdNYmOsp0JvIW1hoC74QQAvD_BwE&gad_source=1&gclid=CjwKCAjwp8--BhBREiwAj7og15LEvOnd4pqCTEfCy5iSgRbU25ds0fdi55EgCMySdNYmOsp0JvIW1hoC74QQAvD_BwE&gclsrc=aw.ds)

KeyPad : 1824 [link](https://www.digikey.com/en/products/detail/adafruit-industries-llc/1824/7244947)

Display: NHD-0216BZ-RN-YBW [link](https://www.digikey.com/en/products/detail/newhaven-display-intl/NHD-0216BZ-RN-YBW/1701194?_gl=1*u09laz*_up*MQ..*_gs*MQ..&gclid=CjwKCAjwp8--BhBREiwAj7og15LEvOnd4pqCTEfCy5iSgRbU25ds0fdi55EgCMySdNYmOsp0JvIW1hoC74QQAvD_BwE&gclsrc=aw.ds)



# Open Source Projects Used
N/A

# Previously Discussed Content
Repurposing portions of aesd-socket 
Repurposing web server from another class

# New Content
Hardware integration, remote identity management, 

# Shared Material
N/A

# Future Work
Refactor Python Hardware Integration code into C/C++, Python isn't handled well for Buildroot and daemons

Integrate Refactored Hardware Integration code into Vending Machine service, keeping it over-complicated the work

Implement core Vending Machine service correctly with stock keeping functionality, i.e. database integration

Implement barcode scanner, determined as a nice to have not a need to have for PoC

# Source Code Organization
TBD: Modify the content below:

Buildroot or Yocto Repository will be hosted at [Project Repo](https://github.com/ldmacdonald/ECEA-5307_Projects)

Vending Machine code will in a repository at [Vending Machine Repo](https://github.com/ldmacdonald/ECEA-5307-Vending_Machine)

Identity Mock code will be hosted in a repository at [Identity Mock Repo](https://github.com/ldmacdonald/ECEA-5307-Identity-Mock)

Hardware Integration code will be hosted in a repository at [Hardware Integration Repo](https://github.com/ldmacdonald/ECEA-5307-Hardware_Integration)

## Team project members:

Dale MacDonald, sole contributor

# Schedule Page
[Schedule](./Schedule.md)

# Blockers Identified

None identified at this time
