# Roster-Creation-Tool
A CAC Barcode scanning tool to automate the physical roster signing process

This program is an expansion on jkusner's CACbarcode python script that can be found here: https://github.com/jkusner/CACBarcode

The program adds a GUI that prompts users to start scanning the back of their Common Access Card (CAC), it displays the extracted EDIPI's in a listbox, and is then input into an excel worksheet that is formatted for the USAF's training portal import tool. Pressing the "Save Roster" button simply saves the roster in the same directory as the executable, pressing the "Transmit Roster" button sends the roster as an email to the address specified by the user, and also saves the roster.

I'm running into an issue where if the user presses "Save Roster" first, then attempts to press the "Transmit Roster" button, the roster won't be transmitted. Please feel free to iterate on this as you please, the source code will be provided and can be manipulated to make the application do whatever you want. Logic is included for use with 2D scanners to scan the front of the CAC as well, which includes more information.
