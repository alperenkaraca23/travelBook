```markdown
# Travel Book App

Travel Book is an application designed to help users save locations and take notes of places they visit while traveling. The app integrates **MapKit** to display and interact with maps, while utilizing **Core Data** to store the locations and notes for future reference.

## Features

- **Save Locations**: Allows users to save places they visit on a map and add a title for each location.
- **MapKit Integration**: Displays saved locations on an interactive map.
- **Gesture Recognition**: Users can tap and hold on a map to add a new location annotation.
- **Route Directions**: Shows routes from the user's current location to the selected location on the map.
- **Core Data Integration**: Saves location details such as title and coordinates using Core Data for persistence.
- **Delete Locations**: Allows users to delete saved locations.
  
## How It Works

1. **MapKit Integration**:
   - Configured **MapKit** to display a map in the app where users can interact with and view locations.
   - Added annotation functionality to mark specific locations on the map.

2. **Gesture Recognition**:
   - Implemented a **gesture recognizer** that listens for a long press (3 seconds) on the map to add an annotation at the clicked location.

3. **Core Data Integration**:
   - Stored location data (such as coordinates and title) in **Core Data** to persistently save user data.
   - Developed functionality to retrieve saved locations and display them on a dedicated page.
   
4. **Displaying Saved Locations**:
   - Created a page that shows all saved locations and provides options to view them on the map.
   - Implemented a button next to each annotation that, when tapped, opens the map and shows directions from the user's location to the saved location.

5. **Delete Functionality**:
   - Added a **delete button** to allow users to remove saved locations from both the map and the Core Data storage.

6. **Testing**:
   - Performed tests to ensure that location saving, annotation, and map navigation work as intended.

## Requirements

- Xcode 14+
- iOS 15+
- Swift 5.7+
- **MapKit** Framework
- **Core Data** for persistent storage

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/travel-book-app.git
   cd travel-book-app
   ```

2. Open the project in Xcode:
   ```bash
   open TravelBookApp.xcodeproj
   ```

3. Run the project on a simulator or a physical device.

## Video Demo



https://github.com/user-attachments/assets/61ab07f2-cea8-45dd-87c0-98d4c0dbc23a



## Technologies Used

- **MapKit**: For displaying interactive maps and annotations.
- **Core Data**: For storing and retrieving saved locations and notes.
- **Swift**: Programming language for development.
- **UIKit**: For designing the user interface.

## Future Improvements

- Add a search feature to find locations by title or coordinates.
- Enable users to add detailed notes or photos to each location.
- Implement the ability to share locations or generate trip itineraries.
- Integrate location-based reminders for each saved place.
