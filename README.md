# ComputerVision_SonicAutomotive

Description of model:
1.The model takes the following steps to achieve the reading of the mileage:
2.Uses EasyOCR to find all text detections in the image
3.Determines whether a ‘mi’ or ‘km’ text is found.
4.Confirms that the text found is not ‘mph’ or ‘km/h’
5.Checks the largest length detections and confirms if a number is attached to it, and returns it.
6.If a number is not attached to the label text found, returns largest number found in image.
