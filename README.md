# Face_Recogintion and Face_Sort  
Sorting Pictures from a folder containing multiple pictures according to person into specific person_folder.  

## How to Execute
### Step 1: Prepare the Pictures

Place the pictures of individuals you want to sort into a folder named faces. Ensure each picture is named according to the person's name to facilitate the sorting process.

### Step 2: Run the Setup Script

Make sure the setup script is executable, then run it to set up the necessary environment and dependencies.

```
chmod +x setup.sh
./setup.sh
```

### Step 3: Execute the Sorting Script

Run the face sorting script with the name of the folder containing the pictures you want to sort.

```
python3 face_sort.py pictures_folder_name
```

## Important Notes

   - The sorting process may take some time, depending on the number and size of the files.
   - The current code is designed to work only with .png and .jpg files. You can modify the code to support other file extensions if needed.

## Summary

The Face_Recognition and Face_Sort project simplifies the task of organizing photos by utilizing face recognition to sort images into respective folders based on the individuals in them. This project provides a practical solution for managing photo collections efficiently.
