#tarnen
Collection of scripts to aid in the disguise of web applications.

```
tarnen (third-person singular simple present tarnt, past tense tarnte, past participle getarnt, auxiliary haben)

to mask; to camouflage; to disguise
```

This project really came about as I was fooling around with ways to make my ADC do more than just sit there and serve pages. 

---
* TARNEN_ACT_LIKE_WP
** F5 iRule and associated DataGroup that mimics the URL paths of the WordPress CMS. Interlopers are logged to a table with a 10 minute timeout. A management panel is provided at /tablemanage.html to view the current list of bad guys. The CLIENT_ACCEPT method can be modified to weaponize this script - I have provided an example that just drops the connection.

* TARNEN_CLOAK_GENERATOR_TAG
** F5 iRule that removes the Generator Tag that alot of CMS and programs use to identify their output

*TARNEN_CLOAK_HEADERS
** F5 iRule that removes all unneeded headers