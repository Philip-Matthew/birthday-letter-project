# Birthday Letters Project

This project generates personalized letters for each person listed in a text file. The script reads a template letter, replaces a placeholder with the actual name of each person, and then saves the customized letters in a specified output directory.

## Project Structure

## How It Works

1. **Input Files**:
   - The `people.txt` file in the `./Input/People/` directory contains a list of names, each on a new line.
   - The `letter.docx` file in the `./Input/Letter/` directory contains the template letter. The placeholder `[name]` is used where the person's name should be inserted.

2. **Script Execution**:
   - The script reads all names from `people.txt` and the content of `letter.docx`.
   - For each name in `people.txt`, the script replaces the `[name]` placeholder in the template letter with the actual name.
   - A new file is created for each person in the `./Output/EditedLetters/` directory, named `letter_for_<name>.docx`.

3. **Output**:
   - The output will be a collection of personalized letters in the `./Output/EditedLetters/` directory.

