# Algumas imagens pré montadas
* RaspberryPi 2 com dongle wifi compatível com RTL8192 https://www.dropbox.com/s/7rhrjwkuv2j5o42/caixamagica_raspberry_PI2B_RTL8192CU.img.xz


Para gravar a imagem no cartão, no linux, descompacte a imagem 

` $ xz -x (nome arquivo imagem) `

Depois use o DD para gravar

` $ dd if=(nome arquivo imagem) of=/dev/(dispositivo do cartão) bs=4096 `
