INSTEAD OF DOWLOADING THE WHOLE ZIP FILE . IT IS RECOMMENDED TO DOWNLOAD THE POWERBI FILE ALONE .

WHEN YOU CLICK DOWNLOAD AFTER CLICKING THE Pbix FILE IT MAY TAKE FEW MINUTES TO START DOWNLOAD (Because the Original file is fetched from the Git LFS server)

REASON:
If you download the entire repository as a zip file and extract it, the PowerBI file will only be 1 KB because the file size is large and uses Git LFS (Large File Storage). The size difference you see (600 MB to 1 KB) is because you are downloading the pointer file, not the actual content. These pointers contain metadata and the URL to the actual file stored on the Git LFS server.

NOTE: [I would not recommend you to download the whole zip file unless and untill you have git and git lfs installed to read the pointer file and pull the original file from Git lfs server]
