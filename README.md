# notes
A collection of notable notes.
## Windows
### How to retrieve the Windows OS Product Key on a old or new computer?
- Press `Windows Key` + `X`
- Click on `Windows PowerShell (Admin)`
- At the `Windows PowerShell`, enter this command:
  ```
  wmic path SoftwareLicensingService get OA3xOriginalProductKey
  ```
