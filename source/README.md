# Building Your Challenge

Found an image `a` on
https://www.muralunique.com/product/jungle/

Created a hint audio by using FakeYou website
https://fakeyou.com/weight/weight_nrqp1vqv1sqmw41kzw4abstas/dora-the-explorer

Generated Ceaser cipher text based on the flag.

Created another audio file using website
https://signals.nitrocosm.com/go/spectrum_text/  
to encode cipher text in its spectogram.

Put both recordings in the treasureChest folder and zipped it.

Created image `b`, which has the zip file embedded in image `a`, by running the following command:
`$ cat a.jpeg treasureChest.zip > b.jpeg`
