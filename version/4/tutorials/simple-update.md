## How To Update Your Raspberry Pi 4


### Simple update:

1. update package information
    ```bash
    sudo apt-get update
    ```

2. upgrade everything, resolving dependencies
    ```bash
    sudo apt-get dist-upgrade -y
    ```

3. If needed we remove old packages.
    ```bash
    sudo apt-get autoremove -y
    ```

4. Clean apt-get
    ```bash
    sudo apt-get clean
    ```

5. Just Reboot you never know.
    ```bash
    sudo reboot
    ```
