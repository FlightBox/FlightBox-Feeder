## Changing IP Address or Host and Port

If you need to modify your IP address, host, or port after the installation of our script, follow these steps:

1. Open the configuration file using nano:
    ```bash
    sudo nano /etc/fbfeeder.conf
    ```

2. Make the necessary changes to the configuration.

3. Save and exit the editor:
   - Press `CTRL + X` to exit.
   - Press `Y` to confirm changes.
   - Press `ENTER` to save.

4. After making changes, restart the fbfeeder service by running:
    ```bash
    sudo systemctl restart fbfeeder
    ```
