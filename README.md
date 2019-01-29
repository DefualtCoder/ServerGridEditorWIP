# ServerGridEditorWIP

This is Grapeshot Games ServerGridEditor. All rights belong to them!

The Official Repository can be found at [GrapeshotGames/ServerGridEditor.](https://github.com/GrapeshotGames/ServerGridEditor)


### Changes Include:

* Corrected Forms.
* Form scrollbars where needed.
* Fixed ToolStripMenu Items
* Various Form Fixes
* Added Quest Form to MainForm as PowerSton Button.
* Added Autopopulate and Save to ServerGrid.json Quest Entries.
* Added Default Grid 1x1 at 1400000 with UTC on at 0.0 upon creation of new project


## Quest Form 

This form was added to make it more simplistic to add your quest entries with the right calculations.

- First and foremost each Zone that a Powerstone is in is Indexed from 0 to 9 and listed as 1-10.
- This form is index based! So Powerstone 1 is PowerStone Index 0.
- This is the **PowerStone** Button located on the MainForm.
- Generate Button shows your the Entry before Applying it.
- The Apply button will not show unless Generate button is clicked.
- Apply Button will replace globalGamplaySetup Property with the updated Calculations.

##### Current Form.
![Current Form Layout](https://i.imgur.com/mQP2GBi.png)

##### Can generate zero values for Powerstone you do not have on map.
![Generate Button Clicked](https://i.imgur.com/A96W4iz.png)

##### Compared with 15x15 Official JSon property.
![After Apply Button Clicked and Project Saved](https://i.imgur.com/ZGsxuTm.png)


# Source

The source of this PR is now available to all. As of 28 Jan 2019, I have pushed this PR to the Original ServerGridEditor Repo!

If you have any questions or found any issues, please ask/report in the issues section.

**_~Default_**

### Licensing/Copyright Information

Grapeshot Games License information can be found here: [Licensing MIT](https://github.com/GrapeshotGames/ServerGridEditor/blob/master/LICENSE)
