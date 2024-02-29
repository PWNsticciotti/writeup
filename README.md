# PWNsticciotti's writeps

In this repository, you can find all the writeups for each of the CTFs we participated in.

## Repository structure

For each CTF you can find the specific folder with the name `[year]_[ctf name]`.

Each writeup folder is based on the structure you can find in the folder called `.template` in this repository.

## How to add your writeup

To add your writeup to this folder you need to:

1. Fork this repository, if you don't have done so yet.

2. Create the folder for the CTF, if don't exist. There are no specific constraints on how to call the folder, we recommend calling the folder in snakecase.

   For example, if the CTF is called `Bambi CTF` and it's played in 2024, the name will be: `2024_baby_ctf`

3. Create the challenge folder with the structure inside the `.template` folder. There are no specific constraints on how to call the folder, we recommend calling the folder in snakecase.  

   For more info, what the files contain and what files are required or optional, check the section below.

4. Create a pull request from your repository towards this repository.

   We suggest creating a pull request for each writeup titled with the name of the writeup itself and the CTF name.

## Writeup folder's structure

Inside the writeup folder you can find the following files and folders:

- `README.md`: contains all the information on the challenge and the writeup, like name, category, description, solving process and flag;

- `exploit.py`: example file that represents a hypothetical script used to "exploit" the challenge;

- `images`: a folder that contains all the images used in the writeup. It's not mandatory but it's recommended to add some images to the writeup if they can facilitate understanding;

- `dist`: a folder that contains all the files that are provided with the challenge. For example: binary files, source code, images, etc.

You can add any other folder if you think they may be necessary.
 