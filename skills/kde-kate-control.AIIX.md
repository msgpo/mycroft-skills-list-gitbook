---
description: 
---
KDE-Kate-Control

#### Installation of skill:
* Download or Clone Git (run: git clone https://github.com/AIIX/kde-kate-control inside /opt/mycroft/skills)
* Create /opt/mycroft/skills folder if it does not exist
* Extract Downloaded Skill into a folder. "kde-kate-control". (Clone does not require this step)
* Copy the kde-kate-control folder to /opt/mycroft/skills/ folder

#### Installation of requirements:
##### Fedora:
- sudo dnf install dbus-python
- From terminal: cp -R /usr/lib64/python2.7/site-packages/dbus* /home/$USER/.virtualenvs/mycroft/lib/python2.7/site-packages/
- From terminal: cp /usr/lib64/python2.7/site-packages/_dbus* /home/$USER/.virtualenvs/mycroft/lib/python2.7/site-packages/

##### Ubuntu / KDE Neon:
- sudo apt install python-dbus
- From terminal: cp -R /usr/lib/python2.7/dist-packages/dbus* /home/$USER/.virtualenvs/mycroft/lib/python2.7/site-packages/
- From terminal: cp /usr/lib/python2.7/dist-packages/_dbus* /home/$USER/.virtualenvs/mycroft/lib/python2.7/site-packages/

* For other distributions:
- Python Dbus package is required and copying the Python Dbus folder and lib from your system python install over to /home/$USER/.virtualenvs/mycroft/lib/python2.7/site-packages/.

**Github:** | (https://github.com/AIIX/kde-kate-control)  
**Owner:** | [@AIIX](https://github.com/AIIX)  
**Created:** | 2017-11-28T13:32:40Z  **Last updated:** 2017-12-08T08:54:08Z  
**License:** | [GNU General Public License v3.0](https://api.github.com/licenses/gpl-3.0)  
**Market status:** | [Not in Market](https://market.mycroft.ai/skill/)  
 ![.gitbook/assets/mark-1-icon.png]  ![.gitbook/assets/mark-2-icon.png]  ![.gitbook/assets/picroft-icon.png]  ![.gitbook/assets/kde.png]  