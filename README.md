# LBFtool

This is a fork of an existing repo by [Mysak0CZ](https://github.com/Mysak0CZ).

[Link to the Original Repo](https://github.com/Mysak0CZ/LBFtool)

This Python script extracts files from LG's proprietary archive format created by the LG Bridge software, which uses the ".lbf" extension.

I was able to successfully extract all 50 GB of data from my LG Wing ".lbf" backup file



## Usage
1) Clone or download this repository to the folder where the .lbf file is located.
     ```bash
     git clone https://github.com/kingshah13/ExtractLGBackupFile.git
     ```
3) Install python 3 if you haven't already.
4) Install pycryptodome.
      ```bash
    pip install pycryptodome
    ```
6) Edit Settings inside extract<i></i>.py (if needed)
7) Run the script: "python extract<i></i>.py LGBackup_xxxxxx.lbf"
    ```bash
    python extract.py LGBackup_xxxxxx.lbf
    ```


## Options & Settings

**TRY_PATH_RECONSTRUCT:** Attempts to reconstruct media paths. Set False if errors occur.

**FORCE_NEW_HEADER:** Forces use of new header format.

**FORCE_OLD_HEADER:** Forces use of old header format.

**EXPORT_DIR:** Set the output directory (default: ./export/).


If you are interested in technical details see this [XDA-developers post](https://forum.xda-developers.com/android/general/tool-lg-restore-com-lge-bnr-lbf-file-t4053579)
