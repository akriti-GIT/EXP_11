# EXP 11 – Google Maps Integration in Android using Kotlin

## Aim
To develop an Android application using Kotlin that integrates Google Maps and provides location-based functionality such as searching locations, displaying map markers, changing map types, and controlling map zoom levels.

## Objectives
- To integrate Google Maps SDK into an Android application.
- To understand Google Maps API and its implementation.
- To search locations using the Geocoder class.
- To display markers at selected geographical locations.
- To implement different map types such as Normal, Satellite, Terrain, and Hybrid.
- To implement zoom-in, zoom-out, and reset location controls.
- To understand WebView integration using Leaflet Maps.

## Theory

Google Maps is a mapping service that provides geographical information, location searching, navigation, and interactive maps.

In Android development, Google Maps can be integrated using the Google Maps SDK for Android.

### Technologies Used

1. **Kotlin:** Programming language used to develop the Android application.
2. **Android Studio:** IDE used for application development.
3. **Google Maps SDK:** Used to display interactive maps.
4. **Geocoder:** Converts location names into geographical coordinates (latitude and longitude).
5. **WebView:** Displays web-based map content inside the Android application.
6. **Leaflet.js:** JavaScript library used to display interactive maps using OpenStreetMap tiles.
7. **XML:** Used to design the application interface.

## Application Description

The application provides an interactive map interface where users can search and explore different geographical locations.

The application includes the following features:

### 1. Student Information
- Displays student name and USN.
- Allows users to enter or modify student details.
- Displays student information in the location marker.

### 2. Location Search
- Allows users to search for locations by entering their names.
- Uses the Android Geocoder class to obtain latitude and longitude.
- Updates the map to the searched location.

### 3. Quick Location Selection

The application provides predefined location buttons for:
- Bengaluru
- New Delhi
- Mumbai
- Taj Mahal
- London

### 4. Map Type Selection

The application supports four map types:

- **Normal:** Displays the standard road map.
- **Satellite:** Displays satellite imagery.
- **Terrain:** Displays geographical terrain information.
- **Hybrid:** Combines satellite imagery with map labels.

### 5. Map Markers
- Displays a marker at the selected location.
- Shows student name and USN in the marker information window.
- Updates the marker whenever a new location is selected.

### 6. Zoom Controls
- Zoom In: Increases the map magnification.
- Zoom Out: Decreases the map magnification.
- Reset Location: Returns the map to Bengaluru.

### 7. WebView Map Integration

The application also uses WebView with Leaflet.js and OpenStreetMap to provide an alternative map rendering interface.

## Important Classes and Methods

| Class / Method | Purpose |
|---|---|
| MainActivity | Main application activity |
| OnMapReadyCallback | Handles Google Map initialization |
| SupportMapFragment | Displays Google Maps |
| Geocoder | Converts location names into coordinates |
| LatLng | Represents geographical coordinates |
| MarkerOptions | Configures map markers |
| CameraUpdateFactory | Controls map camera and zoom |
| WebView | Displays web-based maps |
| FragmentTransaction | Used to manage map fragment placement |

## Procedure

1. Open Android Studio.
2. Create a new project using the Empty Views Activity template.
3. Select Kotlin as the programming language.
4. Add the required Google Maps and Location dependencies in the Gradle file.
5. Add Internet and location permissions in AndroidManifest.xml.
6. Configure the Google Maps API key.
7. Design the user interface using activity_main.xml.
8. Create MainActivity.kt and implement OnMapReadyCallback.
9. Initialize Google Maps using SupportMapFragment.
10. Implement location searching using Geocoder.
11. Add predefined location buttons.
12. Implement map type selection and marker functionality.
13. Add zoom-in, zoom-out, and reset controls.
14. Configure WebView and Leaflet.js as an alternative map display.
15. Run the application on an emulator or Android device.
16. Test all map functionalities.

## Expected Output

1. The application displays an interactive map.
2. Student name and USN are displayed at the top.
3. Users can search for different locations.
4. Predefined location buttons navigate to their respective places.
5. Different map types can be selected.
6. A marker displays the selected location.
7. Zoom controls allow users to zoom in and out.
8. Reset functionality returns the map to Bengaluru.

## Concepts Learned

- Google Maps SDK Integration
- Android Kotlin Development
- SupportMapFragment
- Geocoder and Location Search
- Latitude and Longitude
- Map Markers
- Map Type Configuration
- CameraUpdateFactory
- WebView Integration
- Leaflet.js and OpenStreetMap
- Android Internet Permissions

## Result

Successfully developed and executed an Android application using Kotlin and Google Maps integration. The application supports location searching, predefined locations, map markers, multiple map types, zoom controls, and WebView-based map rendering.

## Conclusion

Through this experiment, we learned how to integrate Google Maps into an Android application using Kotlin. We understood how to search locations using Geocoder, display markers using latitude and longitude, control map zoom levels, and implement different map types. We also explored WebView integration with Leaflet.js for displaying interactive maps.
