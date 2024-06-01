<img src="https://upload.wikimedia.org/wikipedia/commons/1/1f/Bismillah_Calligraphy5.svg" width="350"/>

# Quran Image Assets

This repository contains image assets for the Quran, organized by different models or styles of the Quran. Each model or style has its own folder at the root level (e.g., md, id, kata, hafalan, etc.).

## Quran Models/Styles
The following Quran models/styles are included in this repository:
- md: Madinah model 
- id: Indonesia model 
- kata: Word-by-word model 
- hafalan: Easier to memorize model
- tajwid: Tajwid (Quranic recitation rules) model

## File Structure
Each folder representing a Quran model/style contains the image assets for the corresponding Quran pages. Additionally, each folder (except for the hafalan folder) includes a map.json file, which contains data about the verse blocks and the dimensions of the images.

## _map.json_ File
The map.json file in each folder (except hafalan) provides the following information:
- data: An array of objects, each representing a verse block. Each block object has the following properties:
- surah: The surah (chapter) number.
- ayah: The ayah (verse) number.
- blok: The block number.
- top: The top position of the block on the image.
- left: The left position of the block on the image.
- width: The width of the block.
- height: The height of the block.
- viewportWidth: The width of the Quran page image.
- viewportHeight: The height of the Quran page image.
This information can be used to map the verse blocks to their corresponding locations on the Quran page images.

## Usage
You can use the image assets in this repository for various purposes, such as:
- Building Quran reading applications
- Integrating Quran images into your projects
- Creating custom Quran-related materials
Please note that the use of these assets may be subject to licensing or attribution requirements. Refer to the repository's license information for more details.

## How to access the content
You can access quran content from this repo via free CDN service like jsdelivr or statically.io, eg:
* https://cdn.jsdelivr.net/gh/agusibrahim/quran-image@main/kata-tajwid/001.png
* https://cdn.jsdelivr.net/gh/agusibrahim/quran-image@main/kata-tajwid/map.json
> or
* https://cdn.statically.io/gh/agusibrahim/quran-image/main/md-tajwid/001.png
* https://cdn.statically.io/gh/agusibrahim/quran-image/main/md-tajwid/map.json

If you have any questions or issues, feel free to open an issue in the repository.
