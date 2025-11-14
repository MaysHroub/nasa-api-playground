# 🌌 NASA Explorer (RESTful)

## Group Members

| Name                | Student ID |
| ------------------- | ---------- |
| Bailasan Qadan      | *1220687*  |
| Mays Al-reem Hroup  | *1220081*  |


##  Project Overview

**NASA Explorer** is a web based client application that consumes multiple **official NASA RESTful APIs** directly from the frontend using JavaScript (Fetch API).
The website showcases beautifully designed individual pages for each NASA API with animated cosmic UI, custom backgrounds, and responsive layouts.

This project fulfills **Part 2** of the assignment:

* Consuming REST APIs directly from the frontend
* Displaying live NASA data
* Applying REST principles (resources, endpoints, HTTP methods, representation formats)

Each NASA API is represented on its own standalone page (APOD, Mars Rover, NeoWs, DONKI, EONET, Image Library, TechTransfer).


## API Used

We selected the full NASA API collection from:

🔗 **[https://api.nasa.gov/](https://api.nasa.gov/)**

Our frontend consumes the following APIs:

* **APOD** – Astronomy Picture of the Day
* **Mars Rover Photos API**
* **NeoWs** – Near-Earth Objects Web Service
* **DONKI** – Space Weather Database
* **EONET** – Natural Event Tracker
* **NASA Image & Video Library API**
* **TechTransfer API**

All APIs are accessed via **GET** requests and return **JSON** representations.


## Features

* Fully animated cosmic UI
* Visual theme (Galactic Storm)
* Responsive layout (mobile & desktop)
* Clean separation of pages (each API has its own HTML file)
* Fetch API integration with real NASA endpoints
* Tiles navigation + floating cosmic effects
* Light glass morphism UI panels


## REST Principles Demonstrated

Our frontend illustrates key REST concepts:

### **1. Resource Representation**

Example:
`/planetary/apod` is a **resource** representing NASA’s astronomy media for a specific day.

### **2. Root Resource URL**

```
https://api.nasa.gov
```

### **3. Resource Paths**

Examples:

```
/planetary/apod
/mars-photos/api/v1/rovers/curiosity/photos
/neo/rest/v1/feed
```

### **4. HTTP Method Used**

All requests use:

```
GET
```

### **5. Response Formats**

* JSON (default)
* Some APIs also optionally support different formats

### **6. Query Parameters**

Examples:

```
?api_key=DEMO_KEY
&date=2023-10-01
&sol=1000
&camera=FHAZ
```


## How to Run the Project

### **Requirements**

* Any browser (Chrome recommended)
* No backend required
* Optional: VS Code Live Server extension

### **Steps**
1. Open the file index.html
2. Start the project:

   * If using VS Code → right-click `index.html` → **“Open with Live Server”**
   * OR simply double-click `index.html` to open it in a browser
3. Browse through the NASA API pages and watch the live data load from real NASA endpoints.


## Conclusion

The NASA Explorer project demonstrates real consumption of RESTful Web Services, understanding of REST architecture, and a creative, immersive UI design.
It also provides a full frontend experience using real NASA data across multiple public APIs.
