# **Neighborhood: Prospect Heights**

## An image of Prospect Heights

'''python
#Importing libraries
import numpy as np
import matplotlib.pyplot as plt
img = plt.imread('img.png') #Reads the image
plt.imshow(img) #Loads the image into pyplot
#Creating a copy of the image
img2 = img.copy()
#Graying the TOP area out
img2[:200,:,0] = .5
img2[:200,:,1] = .5
img2[:200,:,2] = .5
#Graying the BOTTOM out
img2[-200:,:,0] = .5
img2[-200:,:,1] = .5
img2[-200:,:,2] = .5
#Graying the LEFT out
img2[:,:500,0] = .5
img2[:,:500,1] = .5
img2[:,:500,2] = .5
#Graying the RIGHT out
img2[:,-500:,0] = .5
img2[:,-500:,1] = .5
img2[:,-500:,2] = .5
#Showing & saving the new image
plt.imshow(img2)
plt.show()
plt.imsave('modified.png', img2)
'''
![alt text][logo]

[logo]: https://static01.nyt.com/newsgraphics/2016/02/16/living-map/969b41227609944c96b9dbc151b92c55dfacee4d/0221-rea-web-LIVINGprospectheights-300.png "Logo Title Text 2"

## Some Demographics & Statistics of Prospect Heights
#### Demographics:
#### Residents of Prospect Heights come from a wide range of backgrounds, resulting in a vibrant
#### tapestry of cultures. The breakdown of the demographics includes:
#### ● Population: Approximately 68,000 residents.
#### ● Ethnicity:
#### White 51.8%
#### Black 26.3%
#### Hispanic 8.1%
#### Asian 7.7%
#### Other 6.1%
#### ● Education: A high percentage of residents holding college degrees.
#### ● Income: A mix of income levels with the average being around 158K
#### ● Languages: A multitude of languages spoken due to the neighborhood's diversity,
#### including English, Spanish, Chinese, and others.

## The Clean Heat Program
#### The NYC Clean Heat program advocates for sustainable heating and cooling, emphasizing the use of heat pumps to eliminate reliance on fossil fuels, benefiting both the environment and individual health. It encourages the installation of various heat pump technologies. The discussion also touches upon the environmental impact of different fuel oils and introduces initiatives like the DEP Boiler Registration and the Greener Greater Buildings Plan, aimed at reducing pollution and enhancing energy efficiency in NYC buildings. The transition to clean heating fuels is highlighted, stressing the need for careful decision-making, proper financing, and effective management to ensure a smooth and environmentally conscious shift in the building sector.
