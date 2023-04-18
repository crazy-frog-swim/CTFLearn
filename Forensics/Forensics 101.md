# Forensics 101
`Forensics`
`Easy`

### Description

Think the flag is somewhere in there. Would you help me find it? _https://mega.nz/#!OHohCbTa!wbg60PARf4u6E6juuvK9-aDRe_bgEL937VO01EImM7c_
<br><br>


## Solution with Linux
1. Download the image into the desire location
2. Open command prompt go to the store image location
3. Use **_strings_** to shows all the string character in the file.
   <br> The flag is inside, but, many irrelevant data also shows.

<br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/117136072/232677651-799158cc-e518-4f48-a7cb-9cf867eccb9a.png">
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/117136072/232676896-e696a656-3203-4df3-b38e-b0f32cdd2999.png">
</p>
<br><br>

4. Use **_grep_** function to show only the data that contain symbol **{** only, shorten the data that show

<br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/117136072/232677736-45f9cf37-4edf-461e-a5aa-35ec82017da6.png">
</p>
