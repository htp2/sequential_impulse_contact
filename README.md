Adnan Munawar, Henry Phalen

Python and cpp examples for finding impulses / forces using the sequential impulse technique

For plotting, the cpp version uses Boost, and also GNUplot

```bash
sudo apt-get install gnuplot libgnuplot-iostream-dev
```

To build cpp version

```bash
git clone https://github.com/htp2/sequential_impulse_contact.git
cd sequential_impuse_contact
mkdir build
cd build
cmake ..
make
```
The exectuable should be called ```sequential_impulse_contact_example``` and is located in the ```build``` directory
