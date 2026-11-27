# Friday office pilot — small copy/paste parts

Distribution: **parts-r1**. The app payload stays **daily-reporting-office-20261127-r2**.

1. Create a fresh writable handoff folder beside your pilot app copy.
2. Open each **Raw text** link below. In that page press **Ctrl+A**, then
   **Ctrl+C**. Paste into a blank plain-text editor and save as the exact
   filename shown, using **UTF-8**. Keep all 20 separate files in the same folder.
   The order is `PART_01.txt`, `PART_02.txt`, …, `PART_20.txt`.
   **Copy each part into its own file. Do not append parts manually.**
3. Copy [JOIN_PARTS.py.txt — Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/JOIN_PARTS.py.txt) the same way and save
   it as **JOIN_PARTS.py.txt** in that same folder. The `.py.txt` ending is intentional.
4. Open the approved Miniconda Prompt/Python environment in that folder.
   Use the working Coupon Lab environment with **Python 3.12 or newer**.
   The joining helper uses the standard library; no package installation is needed.

```text
python JOIN_PARTS.py.txt
```

It checks every part, restores its exact original line endings/tail, and creates
`COPY_ME_FIRST.py.txt`. UTF-8 BOM, Windows CRLF and missing/extra final blank lines
are accepted. Keep all other content unchanged. A failed check names the file
that needs repasting. An existing different installer is preserved; use a fresh
folder. An existing identical installer is accepted without overwriting it.

5. When assembly succeeds, run:

```text
python COPY_ME_FIRST.py.txt --guide
```

Open the created **FRIDAY_OFFICE_GUIDE.txt** and use **WEEKEND_RETURN.txt** as the
results sheet. The third extracted file is **RUN_OFFICE_CHECKS.py.txt**. Follow
the guide to check the pilot app copy before applying its update. Assembly and
`--guide` create handoff files only; they do not update the app.

| Save as this exact filename | Open the small part |
| --- | --- |
| `PART_01.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_01.txt) |
| `PART_02.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_02.txt) |
| `PART_03.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_03.txt) |
| `PART_04.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_04.txt) |
| `PART_05.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_05.txt) |
| `PART_06.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_06.txt) |
| `PART_07.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_07.txt) |
| `PART_08.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_08.txt) |
| `PART_09.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_09.txt) |
| `PART_10.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_10.txt) |
| `PART_11.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_11.txt) |
| `PART_12.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_12.txt) |
| `PART_13.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_13.txt) |
| `PART_14.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_14.txt) |
| `PART_15.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_15.txt) |
| `PART_16.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_16.txt) |
| `PART_17.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_17.txt) |
| `PART_18.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_18.txt) |
| `PART_19.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_19.txt) |
| `PART_20.txt` | [Raw text](https://raw.githubusercontent.com/mojizzle117/coupon-lab-daily-reporting-pilot-20261127-r2/main/PART_20.txt) |

The reconstructed installer must match SHA-256
`4829bac621e1d761496923d39d0b8505e259075a09d71ded4d9cc217702aaa57`.
The helper checks this automatically.
