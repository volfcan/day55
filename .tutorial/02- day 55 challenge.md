# 👉 Day 55 Challenge

Back the 'f' up everybody!

'f' is short for 'file', of course.  What did you think I meant?

Get your minds out of the gutter, go back and get your auto save/load to do list from **Day 51** and use it here.

Your program should:

1. Create a backup folder.
2. Create a random filename.
3. Save a copy of the data to that file.
4. This should all happen **before** the auto save.


<details> <summary> 💡 Hints </summary>
  
- Use a Boolean variable `fileExists` set to False to store whether the file has already been created.
- Use `if fileExists` later on to check the status of the file before creating or writing.
- Use the `os.mkdir()` function.

</details>