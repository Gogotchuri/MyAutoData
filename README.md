# MyAutoData #
Contains data scrapped by [**MyAutoScrapper**](https://github.com/Gogotchuri/MyAutoScrapper) (Written in go)
## Purpose #
Since this data contains real car deals, placed by real humans with pictures, 
It can be used for real world **Machine Learning(*ML*)** or **Machine Vision**.
## Data structure ##
This repository contains *data.csv* file, which has 100 000 car deal detail. Each row representing each deal.
*data.csv* has 18 columns:
- *ID*: Represents unique identifier for each entry, also for each id, there is a sub-folder in images respectively,
  which contains images for the given deal. *ID* is an integer starting from 0.
- *Manufacturer*: A string identifying car manufacturer.
- *Model*: A string identifying car model.
- *Year*: An Integer for the car production year.
- *Category*: A type of the vechile (Sedan, Cabriolet, etc.).
- *Mileage*: An integer representing car mileage in **kilometers**.
- *FuelType*: A Fuel type the car uses.
- *EngineVolume*: A Floating point number, representing engine volume in **litres**.
- *DriveWheels*: A String representing car drive wheels (i.e. Front, Rear, 4x4, etc.).
- *GearBox*: A string to identify gear box of the transmission (Manual, Automatic, etc.)
- *Doors*: A string representing car doors (4, 4/5, etc.)
- *Wheel*: Steering wheel position (Left Wheel, Right Wheel)
- *Color*: Color of the car body.
- *InteriorColor*: Interior color.
- *VIN*: VIN number of the vechile, represented as a string.
- *LeatherInterior*: A boolean value, true if car has a leather interior.
- *Price*: Price of the car in **USD**. If ommited, meants price was set as negotiable. 
- *Clearance*: A boolean value identifying, whether customs has been cleared of not. 

### Important Note! (Disclaimer) ###
None of the fields (Except **ID**) are guaranteed to be filled, or filled with correct information. Since, people sometimes don't enter correct information, or hide some information for reasons. But for most of the entries, most of the fields are supposed to be filled with correct information.
