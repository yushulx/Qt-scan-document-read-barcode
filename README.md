# Qt-scan-document-read-barcode
This is a desktop application developed with Qt Python. It combines [Dynamic Web TWAIN](https://www.dynamsoft.com/web-twain/docs/info/api/?ver=latest) and [Dynamsoft Barcode Reader](https://www.dynamsoft.com/barcode-reader/programming/python/user-guide.html?ver=latest) to implement document scanning and barcode recognition.

## SDK License

**DWT**

[![](https://img.shields.io/badge/Get-30--day%20FREE%20Trial%20License-blue)](https://www.dynamsoft.com/customer/license/trialLicense/?product=dwt)

**DBR**

[![](https://img.shields.io/badge/Get-30--day%20FREE%20Trial%20License-blue)](https://www.dynamsoft.com/customer/license/trialLicense/?product=dbr)

## Install

```bash
pip install -r requirements.txt
```

## Usage
1. Set DWT license in `Resources/dynamsoft.webtwain.config.js`:

    ```js
    Dynamsoft.DWT.ProductKey = "LICENSE-KEY";
    ```

2. Set DBR license in `app.py`:

    ```python
    reader.init_license('LICENSE-KEY')
    ```

3. Run the application:    

    ```bash
    python app.py
    ```  

## Windows Virtual Scanner
If you don't have a physical scanner, you can follow [https://github.com/yushulx/windows-virtual-scanner](https://github.com/yushulx/windows-virtual-scanner) to build and install a virtual scanner, which allows you to scan custom image set.