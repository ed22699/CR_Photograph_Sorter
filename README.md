# CR-Photograph-Sorter

<!--toc:start-->
- [CR-Photograph-Sorter](#cr-photograph-sorter)
  - [Current Workflow](#current-workflow)
    - [What client wants](#what-client-wants)
  - [Ideas](#ideas)
  - [Questions](#questions)
<!--toc:end-->

[Example Website](https://allmark.one)

## Current Workflow
1. Create new folder in the camera for each race/division/category (4-50 boats)
2. Folders with the RAW images are then imported onto a laptop/exteranl SSD (usually import every couple of categories/races)
3. Folders imported into Adobe Lightroom. All images from all the folders appear at once, but remian sorted in their forlers
4. All images are edited and then exported back to their respective folders in JPG format (RAWs also remian in those folders)
5. Edited JPGs only are uploaded to pre-made corresponding folders on our cloud based photo sales platform Zenfolio


### What client wants
After step 4 run through our software which creates a new wolder for each bow number / boatclub
## Ideas 
- Run natively on desktop app (less cost and less file replication)
- CR using python/C++ backend
- Frontend avalonia with dotnet? 
- Frontend use python Qt

1. User selects sport and the relevant tags
2. Look through photos, tag metadata and read all that we can and mark read
3. Extrapolate other photos from those identified
4. Ask user about any photos that could not be identified or could be either or
5. User decides what new folder structure he wants based off these new metadata tags
6. Click confirm and folders will be reorganised on the desktop

## Questions
- How are photos uploaded when there are multiple photographers (timeline)
- Is there an easily accessible database from boat codes to clubs
- Do you want to identify boats in side by side races or should people just look at their final?
- Use race information?
- Add metadata to photos then they decide how to organise
- Are there any similar programs you have found so far? If so what differences would you want?
