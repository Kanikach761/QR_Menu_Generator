# QR_Menu_Generator
* Users can scan the QR code to access a restaurant’s menu online without physical contact, which     promotes hygiene and safety — especially important post-pandemic.
* Automatically generates downloadable QR code images which can be printed and placed on tables, 
  doors, flyers, etc.
# used for :
  Restaurants & Cafes -Share digital menus using QR codes.
                      Stick QR codes on tables for easy customer access.
 Educational Institutions - Use QR codes to link students to notes, resources, and video links.

 # Simple Form Input
Takes a restaurant name and a URL (typically a menu link) from the user through a styled Bootstrap form.
#  QR Code Generation
Uses the qrcode Python library to generate a QR code based on the submitted menu URL.
# Dynamic QR Preview and download feature
After form submission, displays a dynamically rendered QR code image on a new page with the restaurant name.
Provides a direct download link for the generated QR code image.
# Media Handling
Uses MEDIA_URL and MEDIA_ROOT to serve and download QR images correctly.
![home_page](https://github.com/user-attachments/assets/79c796e0-7b71-4f85-8723-8fc851f98cb8)

![download](https://github.com/user-attachments/assets/1c84c2d3-1b61-4969-afec-2082c8f705ff)
![res_name](https://github.com/user-attachments/assets/2eed9161-a741-483f-a978-2b25e5ee1e1c)
