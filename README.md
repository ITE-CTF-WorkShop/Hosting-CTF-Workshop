# Hosting-CTF-Workshop

The Hosting of CTF Workshop aims to let participants learn the process of Challenge Creation and attempt to create their own challenge.

# Contributing to this Repository

1. Clone the repository by using the following command  
   
    ```sh
    git clone https://github.com/ITE-CTF-WorkShop/Hosting-CTF-Workshop.git
    ```

2. Create a Branch of Main and use the following Naming Prefix

    ```
    Category/Challenge Name

    e.g. Digital Forensics/Memory Recovery
    ```

3. Copy the challenge template folder and rename the folder with the Challenge Name

4. Upload all files relating to the challenge into the respective folders

## Challenge Template Folder Content

```
├── Challenge Template
|   ├── distrib
│   │   └── Files for Participants (IF ANY)
|   ├── service
│   │   └── Files for Challenge (IF ANY)
|   ├── solution
│   │   └── Solution Scripts (IF ANY)
|   ├── generate (OPTIONAL)
│   │   └── Files to Regenerate Challenge
|   └── README.MD
```

The template folder contains the following folders

- distrib

Files in this folder will be given to the participants through the CTF platform

- service

If you are craeting a question that has a dockerfile, place your source code here along with the dockerfile

- solution

You may need extra files for your solution explanation (e.g. Screenshots, intermediate files, video proofs). Place them here

- generate (optional)

You may wish to use scripts to create distribution files (to be able to regenerate the questions). You may choose to create this folder to help others

The README.md file must be kept up-to-date. Remember to update the SHA1 hashes of your distribution files if there are any changes.

## Have fun creating!
