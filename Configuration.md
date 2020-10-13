# Configuration

___

### Version

Make sure that you are using **Python3**

___

### Modules

Open up a **terminal** in the **Brutus-folder** and run the following command:**

```shell
$ pip install -m requirements.txt
```

**Or if you should have installed Python3 & Python2:**

```shell
$ pip3 install -m requirements.txt
```

___

### IP address

**Replace** all **HOST-variables** with your **IPv4** address

In order to use it **outside** of your **network** you need to setup **port-forwarding** on your Router & set **HOST** to **"0.0.0.0"** in **'shell.py'**

____
### Folder structure

Make sure that **'brutus.py'**, **'mic_client.py'** and **'camera_client.py'** are in the **same folder**

Make sure that **'shell.py'**, **'mic_host.py'** and **'camera_host.py'** are in the **same folder**
____
### Performing the attack

Open up **'shell.py'**

Run **'brutus.py'** on the **victim's machine**
___