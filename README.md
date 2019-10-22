# Network
This project for study purpose. Visualize computer network and display meaningful data
## Getting Started
These instructions will get you a copy of the project up and running on your local machine
### Prerequisites
Project run on Ubuntu OS and developed using python3 
Addition library:
-igraph
-tkinter
-abc
### Installing
 _Ubuntu 18.04
 ```
sudo apt install ipython3 python3−numpy python3−igraph python3−matplotlib python3−pandas python3−scipy  python3−sklearn
sudo apt install python3-pip
pip3 install bidict 
sudo apt install python3-mpltoolkits.basemap
pip3 install folium
pip3 install geopy
pip3 install requests
pip3 install imageio

```
_Ubuntu 16.04
```
sudo apt install ipython3 python3−numpy python3−matplotlib python3−pandas python3−scipy  python3−sklearn
sudo apt install python3-pip
sudo aptitude install build-essential libxml2-dev libglpk-dev libgmp3-dev libblas-dev liblapack-dev libarpack2-dev python-dev
python3 -m pip install python-igraph
pip3 install bidict 
sudo apt install python3-mpltoolkits.basemap
pip3 install folium
pip3 install geopy
pip3 install requests
pip3 install imageio
```
_Window 10

* download & python 3.6 [Link](https://www.python.org/downloads/release/python-360/)
* download & install pip [link](https://www.liquidweb.com/kb/install-pip-windows/)
* download & install pycairo, python-igraph, basemap via pip [Link](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pycairo)
```
pip install ipython3
pip install numpy
pip install matplotlib
pip install pandas
pip install scipy
pip install sklearn
pip install bidict
pip install folium
pip install geopy
pip install requests
pip install imageio
```

### Support demo
* There are 3 files in "support" folder which support for demo and testing
* Two *.graphml file in order to open a graph
* One *. csv file in order to browse the throughput

### Warning
* The throughput file was generated randomly. Therefore, when testing with throughput statistic, the total number of edges maynot correct because some edges have throughput higher than its bandwidth or capapicity. Therefore those links are not calculated in a chart but still visualized in a graph
