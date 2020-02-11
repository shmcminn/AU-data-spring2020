# Star Wars Speakers

#### By the Los Angeles Times

Story: https://www.latimes.com/projects/star-wars-movies-female-character-analysis/

Github repo: https://github.com/datadesk/star-wars-analysis

How They Did It
https://www.latimes.com/entertainment-arts/story/2019-12-19/star-wars-movies-female-character-analysis-q-a


1. Transcribe [example video](https://youtu.be/8631ukAVr6g?t=88)
2. Use regex to clean transcription and separate into columns
3. Bring text into excel and count words `=LEN(A1)-LEN(SUBSTITUTE(A1," ",""))+1`
4. Combine LAT data into one file
5. Pivot word count by movie by character
6. Sort pivot