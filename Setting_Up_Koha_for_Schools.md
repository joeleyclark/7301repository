# How to Set Up Koha for School Libraries
To get to this step, follow the [Open School Solutions](https://openschoolsolutions.org/how-to-install-and-set-up-koha-for-schools-part-1/) instructions when installing Koha.
## The Bibliographic Framework
We're going to edit our bibliographic framework in Koha. To do this, open the *Koha administration* page.
<img width="2880" height="1196" alt="Untitled design" src="https://github.com/user-attachments/assets/723b5947-ae15-49d0-8d0b-93e784b7e62a" />
Next, click on *MARC bibliographic framework*
<img width="1950" height="566" alt="test" src="https://github.com/user-attachments/assets/74566d63-b4f8-4823-8b82-0cab2c7445e8" />
In the table, select the actions button in the line with "FA" and "Fast Add Framework" then click *Export*
<img width="1904" height="746" alt="Screenshot 2026-03-12 at 2 20 42 PM" src="https://github.com/user-attachments/assets/6a799499-1cbf-4769-82e9-fc9f57fd5ab2" />
Export the file as a CSV document and then open the file in Excel.
In the top section of the spreadsheet, delete the lines with the tags:
+ 010
+ 050
+ 082
+ 090
+ 099
<img width="1410" height="734" alt="Screenshot 2026-03-12 at 2 31 59 PM 1" src="https://github.com/user-attachments/assets/6ec6045a-fd46-49c4-8ea7-c9115c61aca0" />

In the bottom section of the spreadsheet, repeat that step again. Delete all lines with the tags:
+ 010
+ 050
+ 082
+ 090
+ 099
<img width="830" height="1116" alt="Screenshot 2026-03-12 at 2 40 44 PM" src="https://github.com/user-attachments/assets/987bca9d-a0fc-4af4-abd8-72be4dcc3b58" />
<img width="624" height="740" alt="Screenshot 2026-03-12 at 2 44 43 PM" src="https://github.com/user-attachments/assets/89af656e-75a7-4829-b193-a27fe2af538e" />

In the bottom section of the spreadsheet, enter "5" in the hidden column for these tags:
+ 020 - all except sub-field a
+ 022 - all except sub-field a
+ 100 - all except sub-field a
+ 245 - all except sub-fields a and b
+ 250 - all except sub-field a
+ 260 - all except sub-fields a, b and c
+ 300 - all
+ 500 - all except sub-field a
+ 942 - all except sub-field c
+ 952 - only change 2, b, e, f, i, j, l, m, n, q, r, s, u, v, w, y
<img width="1912" height="484" alt="Screenshot 2026-03-12 at 2 55 54 PM" src="https://github.com/user-attachments/assets/6c28d6f0-9a05-4088-9b92-4ebc8e40487e" />

