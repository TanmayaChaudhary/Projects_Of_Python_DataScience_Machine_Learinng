# Web Images Scrapping

### In this project we scrape the Images for the website

### For this first we request for the data from the website & get the content of the website by **data=BeautifulSoup(requests.get("https://www.pexels.com/search/dogs/").content)**

### Then Find all the images by **mobs=data.find_all("img")**

### Then we get **srcs** from **mobs** & then we find the class of the image from the **mobs srcs** 

### For the downloading & saving of the image we use 

**data=requests.get(d,stream=True).content 
        img=io.BytesIO(data)  #read bytes data 
        imgr=Image.open(img)  
        imgr.save("dogs/dog_"+str(i)+".jpg")**


### Finally we scrapp all the images from the given website