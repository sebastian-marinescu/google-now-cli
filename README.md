# google-now-cli #

Command Line for Google Now, based on <https://github.com/mgomes/GCalc>

## Requirements ##

* Mechanize
* Addressable

## Usage ##

	~> ruby g.rb "20 + 30 * 1/2"
	20 + ((30 * 1) / 2) = 35
   
	~> ruby g.rb 20ft to yards
	20 feet = 6.66666667 yards
   
	~> ruby g.rb 200 pesos to euros
	200 Mexican pesos = 11.1106714 Euros

	~> ruby g.rb time in japan
	2:33 AM Monday, February 1, 2016 (GMT+9)    Time in Japan

	~> ruby g.rb 1234 bytes per second in MBps
	1234 (bytes per second) = 0.001234 MBps

	~> ruby g.rb 1234 bytes per second in MBps
	1234 (bytes per second) = 0.001234 MBps

	~> ruby g.rb 'who invented the Internet?'
	Robert  E. Kahn,Vint Cerf Internet, Inventors

## Changes ##

* 1.0: It's been released into the wild.
* 2.0: Works with other Google Now commands (time, city capitals, important people, etc.)

## Author ##

(c) 2009 Mauricio Gomes

