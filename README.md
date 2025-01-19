# SteganografiLSB-ImageToImage
Steganografi LSB foto ke foto dalam bahasa Python, untuk kompresi dengan metode huffman dilakukan oleh tools online di https://compressjpeg.com/

177006028 - Genta Hayindra Irawan
177006036 - Nabil Ramdhani


## Requirements
diperlukan libray pip, pillow, dan click

## cara menggunakan program ini
untuk melakukan merging kedua foto, gunakan:

     py steganography.py merge --img1=<namacoverimage>.jpg --img2=<namaEmbeddedImage>.jpg --output=<NamaStegoImage>.png
     
untuk melakukan pemisahan dari foto, gunakan:

     py steganography.py unmerge --img=<namastegoimage>.png --output=<namaExtractedImage>.png  
