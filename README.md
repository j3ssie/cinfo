## Cinfo

Extract domain from SSL Information

## Install

```shell
GO111MODULE=on go get -u github.com/j3ssie/cinfo
```

## Usage

```shell
# Basic Usage
echo '1.2.3.4:443' | cinfo
echo '1.2.3.4:443' | cinfo -v -json


# probe for common SSL ports like 443 and 8443 too
echo '1.2.3.4' | cinfo -e

# get alexa rank of IPs / domains
echo '1.2.3.4' | cinfo -e -a
echo 'sub.example.com' | cinfo -e -a
```

## Donation

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://paypal.me/j3ssiejjj)

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/j3ssie)
