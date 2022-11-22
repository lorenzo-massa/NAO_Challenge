# FirenzeReggio_Team

Authors:
* Lorenzo Massa		lorenzo.massa6@studio.unibo.it
* Alessandro Folloni	alessandro.folloni2@studio.unibo.it

## Instructions
Starting from a working instance of the "NaoUbuntu" virtual machine:
  1. Install VLC and GIT:
```bash
sudo apt-get update
sudo apt-get install vlc git
```
  2. Download the repository:
```bash
git clone https://github.com/lorenzo-massa/FirenzeReggio_Team
  3. Get the needed Python3 tools:
```bash
cd FirenzeReggio_Team
pip3 install -U pip setuptools
sudo apt-get install python3-venv
```
  4. Prepare the virtual environment:
```bash
python3 -m venv venv
```
  5. Install the Python3 dependencies:
```bash
. venv/bin/activate
pip3 install -r requirements.txt
deactivate
```
  6. Run the script inside a terminal emulator:
```bash
cd FirenzeReggio_Team
. venv/bin/activate
python3 main.py localhost port
deactivate
```

**To run the script, Choreograph must be opened with a proper virtual robot available for external connections**
**Please, remember to do the following steps before launching the script:**
  1. **open Choreograph**
  2. **go to Edit->Preferences and open the 'General' tab**
  3. **set 'Motor speed (%)' to 100**
  4. **switch to the 'Virtual Robot' tab**
  5. **select the 'NAO H25 (V40)' as the 'Robot model'**
  6. **click on the 'OK' button in the bottom right of the modal window**
