# Yelp Camp Web Application

This web application allows users to add, view, access, and rate campgrounds by location. It is based on "The Web Developer Bootcamp" by Colt Steele, but includes several modifications and bug fixes. The application leverages a variety of technologies and packages, such as:

- **Node.js with Express**: Used for the web server.
- **Bootstrap**: For front-end design.
- **Mapbox**: Provides a fancy cluster map.
- **MongoDB Atlas**: Serves as the database.
- **Passport package with local strategy**: For authentication and authorization.
- **Cloudinary**: Used for cloud-based image storage.
- **Helmet**: Enhances application security.
- ...

## Setup Instructions

To get this application up and running, you'll need to set up accounts with Cloudinary, Mapbox, and MongoDB Atlas. Once these are set up, create a `.env` file in the same folder as `app.js`. This file should contain the following configurations:

```sh
CLOUDINARY_CLOUD_NAME=[Your Cloudinary Cloud Name]
CLOUDINARY_KEY=[Your Cloudinary Key]
CLOUDINARY_SECRET=[Your Cloudinary Secret]
MAPBOX_TOKEN=[Your Mapbox Token]
DB_URL=[Your MongoDB Atlas Connection URL]
SECRET=[Your Chosen Secret Key] # This can be any value you prefer
```

After configuring the .env file, you can start the project by running:
```sh
docker compose up
```

## Application Screenshots
![](./images/campgrounds.jpg)
![](./images/register.jpg)
<img width="948" height="453" alt="Capturejsdksdf" src="https://github.com/user-attachments/assets/2d12525f-2c20-4aa0-ac94-b33490ca850f" />
<img width="949" height="393" alt="fhjhdjhd" src="https://github.com/user-attachments/assets/585ffb35-6402-4205-b090-4890c43d8eaf" />
<img width="954" height="400" alt="sdjdj" src="https://github.com/user-attachments/assets/b8abae2e-cd84-490b-a1f0-3d30cdd40cc0" />

<img width="935" height="471" alt="Capturejsjsd" src="https://github.com/user-attachments/assets/d613d36f-8e19-4506-9dbd-493c49fba30f" />

<img width="960" height="486" alt="Capturejdjd" src="https://github.com/user-attachments/assets/5ae13139-256c-4e55-a482-08bea02deb2d" />


