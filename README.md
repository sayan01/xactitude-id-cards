# xactitude-id-cards
Shell scripts and python scripts to automate the creation of id cards for both participants and organizers of xactitude.

Organizer's cards and scripts are present in `organizers/` and participants cards and scripts are present in `participants/`.

To generate cards run `./genid` in the respective folder.

The `list` file needs to have the data in TSV format.

The `./genqr` script is auto-run but can also be run manually to generate the QR code for each participant (not for organizer).

To remove preexisting images run `rm id/*.png` in the respective folder.

Copyright - Sayan - 2023
