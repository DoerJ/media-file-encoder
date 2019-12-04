# Huffman-LZW-coding-in-Multimedia-System
Lossless data compression on WAV and BMP file, by utilizing Huffman and LZW algorithms
#### Description
The project kit contains serveral programs that read, compress, and uncompress the multimedia files(i.e., uncompressed .wav and .bmp). The key idea of this project is to demonstrate how various kinds of media files are structured in bits, and how the attributes of images such as vue, satuation, and brightness can be adjusted by manipulating the file bits. Moreover, the project demonstates how the size of the media files can be reduced significantly without losing information by utilizing the concepts of information theory and lossless compression algorithms. 
#### Project Structure
- wav_reader/src: Reads a .wav file, and displays the waveform on screen
- bmp_reader/src: Reads an uncompressed .bmp file, process it, and displays on the screen
  - bmp_reader works as follow:
    - Display the origianl coloured image
    - Refresh by the histogram of each channel(R, G, B)
    - Refresh by an image that is 1.5 time brighter
    - Refresh by the grayscale image of the original image
    - Refresh by the ordered dithering on this grayscale image
- ~~wav_decoder/src~~ wav_encoder/src: Reads a .wav file, and compress the file losslessly using Huffman and LZW coding
- IM3_generator/src: Implements an encoder and decoder for a customized lossy image compression format IM3
- IN3_generator/src: Implements an encoder and decoder for a customized lossless image compression format IN3
- images: bmp image samples
- wav: wav samples
- IM3: Lossy image sample IM3 generated by the IM3_generator
- IN3: Lossless image samples IN3 generated by the IN3_generator
