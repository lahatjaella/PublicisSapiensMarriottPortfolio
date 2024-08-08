# Marriott Bonvoy Hotels and Villas Project

Welcome to the GitHub repository for the Marriott Bonvoy Hotels and Villas project. This project involved developing a personalized destination feature and integrating it with an interactive map to enhance user experience on the Homes and Villas website.

## Contents

- [Introduction](#introduction)
- [Provided Code](#provided-code)
- [Tasks Completed](#tasks-completed)
  - [Step 1: Understand Your Market](#step-1-understand-your-market)
  - [Step 2: Understand Your Users](#step-2-understand-your-users)
  - [Step 3: Define and Prototype](#step-3-define-and-prototype)
  - [Step 4: Write Code](#step-4-write-code)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Consulting at PS involves developing digital products like websites and apps to solve complex business problems. This project is based on the Marriott Homes and Villas case study, allowing me to put my coding skills into context and experience a miniature version of the process of creating digital products.

## Provided Code

The provided code includes:
- **PLACES**: An array in `places.js` containing place objects.
- **centerPlaceOnMap(placeName)**: A function that uses the Open Layers API to pan the map to a selected location.

## Tasks Completed

### Step 1: Understand Your Market 

To develop an understanding of our client’s industry, I visited the following three hospitality websites offering whole-home rentals:

1. **[Airbnb](https://www.airbnb.com/)**:
    Airbnb is a significant competitor to Homes & Villas by Marriott Bonvoy due to its extensive reach and brand recognition in the vacation rental market. Offering a diverse range of accommodations from budget to luxury, Airbnb appeals to both leisure and business travelers with its unique, locally-inspired experiences and user-friendly platform. Like Marriott Bonvoy, Airbnb provides various rental options, including homes, villas, and apartments, and emphasizes personalized and authentic stays. Leveraging Marriott's trusted brand and loyalty benefits, Marriott Bonvoy can offer a differentiated, high-quality alternative to Airbnb's offerings.

2. **[VRBO](https://www.vrbo.com/)**:
    Vrbo's emphasis on entire home rentals aligns with the offerings of Homes & Villas by Marriott Bonvoy, which also focuses on providing exclusive access to homes, villas, and apartments. Both platforms prioritize privacy and comfort by offering entire homes, villas, and apartments, setting them apart from competitors that provide shared accommodations or hotel-style rooms. Vrbo's diverse range of property types, such as beachfront houses, mountain cabins, and urban apartments, mirrors Homes & Villas by Marriott Bonvoy's curated selection of luxury homes worldwide. Their emphasis on user-friendly interfaces, detailed property descriptions, high-quality photos, and customer reviews enhances the user experience and aids in customer retention. Vrbo's extensive global presence offers insights into market trends and traveler preferences, which Homes & Villas by Marriott Bonvoy can leverage to strategically position itself in key markets.

3. **[BluePillow](https://www.bluepillow.com/)**:
    BluePillow serves as a valuable resource for Homes & Villas by Marriott Bonvoy, offering strategic insights despite its role as a meta-search engine rather than a direct competitor. By aggregating listings from various platforms, BluePillow enables Marriott Bonvoy to benchmark its pricing and features against a wide range of competitors, facilitating adjustments to pricing strategies. Analyzing BluePillow's data helps identify emerging trends in the vacation rental market, such as popular destinations and guest preferences. Moreover, BluePillow's user-friendly interface and advanced search capabilities provide inspiration for enhancing Marriott Bonvoy's booking platform, incorporating features like personalized recommendations and comparison tools.

### Competitors' Product Features

#### Airbnb Product Features
1. **Interest-Based Discovery**
2. **Inspiration Hub**
3. **Interactive Property Maps & Neighborhood Highlights**
4. **Host Profiles and Communication**
5. **Personalized Profile Management**
6. **24/7 Customer Support**
7. **Search Engine Customizations**
8. **Comprehensive Filtering System**
9. **Dual Viewing Options**
10. **Transparent Pricing Features**

#### VRBO Product Features
1. **Display Settings by Language and Currency**
2. **Search Engine Customizations**
3. **Popular Destinations Gallery**
4. **"Find Places That Suit Your Style" Feature**
5. **Inspiration Hub**
6. **Advanced Search Capabilities**
7. **Side-by-Side View**
8. **Interactive Maps**
9. **Direct Host Communication**
10. **Trip Boards for Group Planning**

#### BluePillow Product Features
1. **Language and Currency Preferences**
2. **Booking.com Comparison Toggle**
3. **Top Destinations and Regions Gallery**
4. **Recommendations for Other Countries and Popular Destinations**
5. **Map and List View Toggle**
6. **Per Night vs. Total Cost Toggle**
7. **Comprehensive Filters**
8. **Map Integration with Proximity to Travel Locations**
9. **Alternative Booking Options and External Site Links**
10. **Personalized Notifications**

### Step 2: Understand Your Users 

#### Themes Emerging from User Research

The user research suggests that while the Homes and Villas website offers some useful features, it lacks key functionalities found on comparable sites like Airbnb and Vrbo. A significant connection between qualitative feedback and quantitative survey results reveals that many users are seeking inspiration and guidance, with 38.67% knowing what type of vacation they want but not having settled on a destination, and 27.44% looking for inspiration entirely. Users express frustration with the overwhelming map and the absence of an inspiration hub to guide their travel planning. They desire more intuitive navigation and the ability to explore destinations by type (e.g., beach, mountain) rather than specific locations. Users also wish for rich, upfront information about destinations and activities. Overall, they seek a more engaging and informative booking experience, akin to the inspiration-focused approach seen on other platforms. This indicates a need for Homes and Villas by Marriott Bonvoy to incorporate features that inspire and simplify the decision-making process for undecided travelers.

### Step 3: Define and Prototype 

#### Prototype Link
[Prototype Link](https://docs.google.com/presentation/d/1j2Uvzyv3aB5GZD5U8MY0nPHc_oEVLplXJdvuyAXeCqk/edit?usp=sharing)

#### Level Up Features

**Feature 1: High-Fidelity Wireframe**
- **Graphics**: Added visually appealing images and icons to create a more engaging user interface.
- **Clicking Functionality**: Implemented basic interactivity, allowing users to navigate through different sections of the website.
- **Colors**: Applied a cohesive color scheme to improve the overall aesthetics and user experience.

**Feature 2: Like/Dislike Destination Functionality**
- **Like/Dislike Buttons**: Users can express their preferences by liking or disliking destinations.
- **Saved Listings Page**: Liked destinations are automatically saved and can be viewed on a dedicated "Saved Listings" page.
- **Personalized User Experience**: Disliked destinations help Marriott Bonvoy curate the user's page, tailoring recommendations to better fit their needs during the current session.
- **Heart Icon and Dream Destinations**: Users can click the heart icon or the "Dream Destinations" link to easily access and manage their saved listings.

### Step 4: Write Code 

#### Task 1 - filterPlacesByType(typePreference)
Filtered the PLACES array to return places matching the user's type preference.

#### Task 2 - createCard(place)
Created a Bootstrap card for a given place object, integrating with the Open Layers API to center the map on the selected place.

#### Task 3 - populateRecommendationCards(filteredPlaces)
Cleared the recommendations section and populated it with cards for the filtered places.

#### Task 4 - findPlaceByName(placeName)
Found a place object in the PLACES array by its name, used to pin the location on the interactive map and fly to it when clicked.

## Technologies Used

- **HTML5 & CSS3**: For structuring and styling the web pages.
- **JavaScript**: For adding interactivity and implementing the specified features.
- **Bootstrap**: For responsive design and styling components.
- **Open Layers API**: For interactive map functionality.

