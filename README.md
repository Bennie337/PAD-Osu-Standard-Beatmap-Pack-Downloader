# P.A.D. Osu! Standard Beatmap Pack Downloader
This is a flow made in [Power Automate Desktop](https://learn.microsoft.com/en-us/power-automate/desktop-flows/install) meant to easily download the standard beatmap packs for all 4 categories in bulk.

My reason in creating this flow within Power Automate Desktop was simply because I wanted to download all Standard Beatmap Packs on the [beatmap pack listing](https://osu.ppy.sh/beatmaps/packs) as well as making it easy to retrieve the latest packs in case the listing gets updated.

For more information about the Beatmap Pack listing, please visit this [official Osu! Wiki page](https://github.com/ppy/osu-wiki/blob/master/wiki/Beatmap/Packs/en.md).

## Downloading the Flow
Firstly, you can download the flow by downloading the .txt file [here](https://github.com/Bennie337/PAD-Osu-Standard-Beatmap-Pack-Downloader/blob/main/PAD_Osu_Standard_Beatmap_Pack_Downloader.txt).
Alternatively, you can also just copy over the text to your clipboard.

## Importing to P.A.D.
Importing is as easy as opening a new flow, giving it a name and pasting the text into the Main flow.

The only thing you need to change is the *downloadMainFolder* variable to your download folder of choice. The flow will automatically make a subfolder for the category you selected to download.

## Running the flow
When you saved your flow and exited the flow editor, simply run the flow.

You will be prompted to input from which beatmap pack you would like to start downloading as well as for which category you would like to download the packs for. 

The download will iterate upwards, downloading until there are no newer packs to download.