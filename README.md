
### VidFinder
VidFinder is a video content search and review platform that leverages React, React Router, React Popup, and React Video Player to provide a seamless user experience. The application supports filtering based on user choices and features secure authentication, light/dark themes, and dynamic routing.

### Features

**Login Route**<br/>

Displays error message for invalid credentials.<br/>
Navigates to Home route upon successful login.<br/>
Redirects unauthenticated users to Login route when accessing restricted routes.<br/>

**Home Route**<br/>

Fetches and displays videos with a loader during data fetching.<br/>
Supports search functionality with dynamic updates.<br/>
Handles HTTP request failures with a retry option.<br/>

**Trending Route**<br/>

Fetches trending videos with a loader and handles HTTP request failures.<br/>
Allows navigation to Home, Gaming, and Saved Videos routes.<br/>

**Gaming Route**<br/>

Fetches gaming videos with a loader and handles HTTP request failures.<br/>
Supports navigation between Home, Trending, and Saved Videos routes.<br/>

**Video Item Details Route**<br/>

Fetches detailed video information and displays it using React Video Player.<br/>
Supports like, dislike, and save functionalities with active/inactive states.<br/>

**Saved Videos Route**<br/>

Displays saved videos or a "No Saved Videos Found" view if the list is empty.<br/>
Supports navigation to other main routes.<br/>

**General Features**
Light theme by default with toggle option.

404 Not Found route for unsupported paths.

Logout functionality with confirmation popup using React Popup.
