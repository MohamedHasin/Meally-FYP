# Meally-FYP
Welcome to the **Meally-FYP** repository. This project contains essential files, including a ZIP file (`meally-app.zip`) with the application's source code and assets. Follow the instructions below to download and extract the ZIP file properly.

## How to Download the ZIP File
### Prerequisites
Ensure you have the following installed on your machine:
1. **Git**: Version control system ([Install Git](https://git-scm.com/))
2. **Git LFS (Large File Storage)**: Required to download large files stored in this repository ([Install Git LFS](https://git-lfs.github.com/))

### Step-by-Step Instructions
1. Clone the Repository:  
Use Git to clone this repository:  
`git clone https://github.com/MohamedHasin/Meally-FYP.git`  
Navigate into the cloned repository:  
`cd Meally-FYP`

2. Install Git LFS:  
If Git LFS is not already installed, initialize it:  
`git lfs install`

3. Pull the ZIP File:  
Download the contents of the `meally-app.zip` file using Git LFS:  
`git lfs pull`

4. Verify the Download:  
Check that the ZIP file has been downloaded successfully:  
`ls -lh`  
You should see the `meally-app.zip` file listed with a size of **158 MB**.

5. Extract the ZIP File:  
Extract the contents of the ZIP file using the following command:  
`unzip meally-app.zip`  
The extracted files will appear in the current directory.

## Troubleshooting
### Issue: ZIP File Doesn’t Download Properly  
Ensure Git LFS is installed and initialized correctly (`git lfs install`).  
Force Git LFS to fetch the file:  
`git lfs fetch --all`  
`git lfs pull`

### Issue: Cannot Locate Extracted Files  
Use the command below to extract the ZIP file to a specific folder:  
`unzip meally-app.zip -d /path/to/destination-folder`

## Repository Contents
- **`README.pdf`**: Documentation for the project.  
- **`meally-app.zip`**: Contains the source code and assets for the application.  
- **`package-lock.json`**: Dependency lock file.
