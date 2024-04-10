# FlightBox-Feeder
To feed FlightBox.org use the commands below:

cd &&
sudo wget https://flightbox.org/downloads/fbfeeder.sh &&
sudo sed -i 's/\r$//' fbfeeder.sh &&
sudo chmod +x fbfeeder.sh &&
sudo ./fbfeeder.sh
