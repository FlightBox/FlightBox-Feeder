# FlightBox-Feeder

This repository contains a script to feed FlightBox.org with data. Follow the steps below to utilize it:

NB! Your receiver must be already running!

1. Open your terminal.

2. Navigate to your home directory using the `cd` command:
    ```bash
    cd
    ```

3. Execute the following command:

    ```bash
    sudo wget https://flightbox.org/downloads/fbfeeder.sh
    sudo sed -i 's/\r$//' fbfeeder.sh
    sudo chmod +x fbfeeder.sh
    sudo ./fbfeeder.sh
    ```

4. Once executed, the script will feed data to FlightBox.org.



