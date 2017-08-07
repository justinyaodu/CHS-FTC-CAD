# Setting up GitHub with CAD

**1. Create a new folder on your computer which will contain all your CAD files. We'll use "MyTinoFtcCad" as an example.**

```
MyTinoFtcCad
```

**2. Create a subdirectory called "CHS-FTC-CAD" (you will be cloning this repository into this folder).**

```
MyTinoFtcCad

|_  CHS-FTC-CAD (empty folder)
```

**3. Create a subdirectory called "FTC-(team number)-(year)-CAD". For example, team 7610 for the 2017-2018 school year would use the name "FTC-7610-2018-CAD".**

```
MyTinoFtcCad

|_  CHS-FTC-CAD (empty folder)

|_  FTC-7610-2018-CAD (empty folder)
```

**4. Clone CHS-FTC-CAD into the appropriate folder. You can use GitHub desktop for this step.**

```
MyTinoFtcCad

|_  CHS-FTC-CAD (repository with CAD resources)

    |_  *repository files*

|_  FTC-7610-2018-CAD (empty folder)
```

**5. If a teammate of yours has already created a repository for your team's CAD files, clone it into the second folder and skip the rest of this step. Otherwise, create a new repository in the second folder, and name it the same as the folder.**

Please copy the following text and paste it into a new file in your new repository named "README.md". Don't forget to add this file to GitHub!

```
# FTC-TEAMNUMBER-SEASONYEAR-CAD

CAD repository for Cupertino High School's FTC team TEAMNUMBER (SCHOOLYEAR).
```

TEAMNUMBER: self explanatory

SEASONYEAR: if the current school year is 2017-2018, use 2018 (for consistency)

SCHOOLYEAR: the current school year (e.g. 2017-2018)

**6. Your folder structure should now look like:**

```
MyTinoFtcCad

|_  CHS-FTC-CAD (repository with CAD resources)

    |_  *repository files*

|_  FTC-7610-2018-CAD (repository which will contain your CAD files)

    |_  README.md
```

You can now pull updated CAD files shared between teams from CHS-FTC-CAD, and you can push and pull your team's CAD models to your team's repository. You're all set!

## Known limitations

Refrain from editing the same part/assembly at the same time as someone else; dealing with merge conflicts in SolidWorks files is more troublesome than just redoing your work.

Assemblies will have to be rebuilt when subassemblies are edited.
