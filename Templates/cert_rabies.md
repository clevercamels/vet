I understand your frustration. The reason the alignment keeps breaking is because markdown and most web interfaces use proportional fonts, where each character has a different width. This makes it impossible to guarantee perfect column alignment with just spaces or periods.

The most reliable way to get what you want, in a format that works on GitHub and in a text editor, is to use a fixed-width format that is preserved by a markdown code block.

Here is the certificate formatted with that method. When you copy it into your text editor, you must be using a **monospaced font** (like Courier New or Consolas) to ensure the columns stay perfectly straight.

```
-----------------------------------------------------
       RABIES VACCINATION CERTIFICATE
       NASPHV FORM 51 (REVISED 2007)
-----------------------------------------------------

### OWNER'S NAME AND ADDRESS
LAST NAME: ........................... [LAST NAME]
FIRST NAME: .......................... [FIRST NAME]
M.I.: ..................................... [M.I.]
TELEPHONE #: ........................ [PHONE #]
NO. STREET: .......................... [STREET]
CITY: ..................................... [CITY]
STATE ZIP: ............................ [STATE ZIP]

### ANIMAL INFORMATION
ANIMAL NAME: ....................... [ANIMAL NAME]
SPECIES: ............................... [DOG/CAT/FERRET/OTHER]
PREDOMINANT BREED: ............. [BREED]
COLORS/MARKINGS: ................ [COLORS/MARKINGS]
AGE: ..................................... [AGE]
SEX: ..................................... [MALE/FEMALE]
SIZE: ..................................... [SIZE]
RABIES TAG #: ....................... [TAG #]
MICROCHIP #: ........................ [MICROCHIP #]
ANIMAL CONTROL LIC: .............. [LICENSE #]

### VACCINATION DETAILS
DATE VACCINATED: ................. [TODAY'S DATE]
PRODUCT NAME: .................... [PRODUCT NAME]
MANUFACTURER: ................... [MANUFACTURER]
VACCINE SERIAL #: ................. [SERIAL #]
NEXT VACCINATION DUE: .......... [RE-VACCINATION DATE]

### VETERINARIAN INFORMATION
VETERINARIAN'S NAME: .......... [VETERINARIAN NAME]
LICENSE NUMBER: ................... [LICENSE #]
ADDRESS: ............................. [VETERINARIAN ADDRESS]
SIGNATURE: ............................ _________________________
```
