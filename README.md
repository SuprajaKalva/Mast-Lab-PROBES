
# Mast Lab - PROBES Implementation 
> This repository contains information regarding the software backend of our rodent odor discrimination apparatus from our paper/lab.

## Requirements

- Download Python
- Buy StremeCoder Software [https://www.stremecoder.com/]
- Download Pip
  - Pip Requirements to run this program:
    - ```sh
        pip install pandas
        pip install simpleaudio
        pip install serial
      ``` 

## Installation

In order to run the program, please download the koi file in the repository and open it up in STREMECODER. Then, make the necessary changes in the nodes using the user inferace of the nodes. After making the changes, click on the compile and run button towards the top of the software to the run the program. 

![Mast_Experiment_Commander_Threshold_Test_B copy-page-001](https://user-images.githubusercontent.com/17326018/113245811-b2066000-9285-11eb-9982-2ef55fdcb56a.jpg)

- Please note that the usb port number for the Arduino/serial port number must be changed within the code under the variable name SERIAL_PORT in the "Connection to Arudino" node.
  - Depending on your operating system, please identify a method to discover the serial port number for the Ardunio.

    ![Screen Shot 2021-04-01 at 12 56 52 AM](https://user-images.githubusercontent.com/17326018/113245835-c185a900-9285-11eb-80ca-790ac62fa5ac.png)
    
    ![Screen Shot 2021-04-01 at 1 02 11 AM](https://user-images.githubusercontent.com/17326018/113245910-ebd76680-9285-11eb-8269-a745a0c74e5d.png)
    
    **Above pictures are a courtesy of: Boloor, A. J., Shah, S., Shah, U., & Schwartz, M. (2016). Arduino: Building LED and Espionage Projects. Packt Publishing.**


## Release History

* 0.0.2
    * First release deployed in lab
* 0.0.1
    * Work in progress

## Meta

Supraja Kalva – skalva@emich.edu -[https://github.com/SuprajaKalva]

Distributed under the GNU GPLv3 license. See ``LICENSE`` for more information.


## Contributing

1. Fork it (<https://github.com/SuprajaKalva/Mast-Lab-PROBES.git>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

## Bugs and Issues

Please report all the bugs and issues to the GitHub issues page with proper labels for them to be fixed and reviewed.
