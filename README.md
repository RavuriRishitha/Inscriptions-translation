# Inscriptions-translation
Inscriptions are like Treasure which tell us about ancient Culture,Civilizations,Medical Practices followed at that time and much more ,which indeed helpful to current technologies in order to obtain progress.
Here is a small work done by me, to obtain Inscriptions and translate them into a comfortable language of user.

Here I took Telugu Inscritions, as Inscriptions extraction is not not yet clear in Telugu( and also bcoz my mother tongue is Telugu :D )

In this work, I created my own Database of handwritten characters and them trained an Image classifier by using MobileNetV2(type of CNN), where we got an accuracy of 84% .

In the model, I have used almost 25 Epoches in order to increase the performance of the model. Also used Adam Optimizer.

Finally output of the work looks like 'Transliterated' script of the character. For example: 'A', 'Aa' , 'E', 'Ee' and so on..

In our future work, we are going to create a Web application on the model in order to make it User-friendly.

Whole work description: - A picture of Inscription is given to the web application as an Input - The Input is Segmented into words. - Then Bounding Boxes are created for each Character of a word from sentence segmentation. - Co-ordinates of Bounding Box are obtained and then cropped with help of co-ordinates. - After obtaining each Character's image, it is sent to model and transliterated output of character is obtained. - Integration of transliterated output - Translation of the integrated transliterated output in a language of user comfort. - Thus we obtain meaning of the Inscription.
