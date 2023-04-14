# Endless Expert (No Skip) Data from Super Mario Maker 2

## Intro

The following dataframe was collected after I completed a run in Endless Expert mode where I beat over 100 levels without skipping. There is an additional /qmd file entitled `fSMM2_EE100_Formatting.qmd` where I show the code that I used to create my dataframe.

The database was created with the help of the [SMM2 TGR API](https://tgrcode.com/mm2/docs/).

## About The Data
| Variable Name | Type | Description                                                                         |
|---------------|------|-------------------------------------------------------------------------------------|
| Level         | int  | The level number                                                                    |
| Course_ID     | chr  | unique level Course ID                                                              |
| Lives_Started | int  | Lives starting level with                                                           |
| Lives_Ended   | int  | Lives after level was completed                                                     |
| Net_Lives     | int  | The difference between `Lives_Ended` and `Lives_Started` (how many lives were lost) |
| Rating        | int  | Rating I gave level, (-1 = Boo, 0 = No Rating, 1 = Love)                            |
| First_Clear   | logi | Stating if I got the First Clear                                                    |
| World_Record  | logi | Stating if I got the World Record on the level                                      |
| Level_Name    | chr  | Level name                                                                          |
| Region        | chr  | Region where the level maker is from                                                |
| Game_Style    | chr  | Style of level                                                                      |
| Game_Theme    | chr  | Theme of level                                                                      |
| Tag_1         | chr  | Level tag                                                                           |
| Tag_2         | chr  | Level tag                                                                           |
| Clears        | int  | Number of clears the level had                                                      |
| Attempts      | int  | Number of attempts the level had                                                    |
| Clear_Rate    | num  | Level clear rate                                                                    |
| Likes         | int  | Number of likes the level had                                                       |
| Boos          | int  | Number of boos the level had                                                        |
| Like_Ratio    | num  | Ratio of Likes:Boos                                                                 |
