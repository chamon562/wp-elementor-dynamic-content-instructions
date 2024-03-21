# wp-elementor-dynamic-content-instructions
This is a detailed over view of how to utilize 2 plugins will give wordpress elementor users the ability to create, store, and use dynamic data that will be later used in a template page. This type of data can be used to populate information for a blog post, or location page.
# Objective
We will first download the plugins and set up the data first, then create a template page that will later be populated with our created custom data. So we dont have to keep creating separate pages for how ever many locations.
# Plugins to download
1. Plugin name: Advanced custom fields (ACF)
    - Go to plugins in the wordpress admin dash and type in the search Advanced custom fields. 
    - download and click activate changes. 
    - Refresh your wordpress if needed and should see ACF on the left dash.
2. Hover over ACF and click Post Types. Make sure on the more tab or the tab is on Post types. 
3. Click the + Add New Button. 
4. In this example I will be creating a main Locations.
5. Plural Lable : Locations
6. Singular Label: Location
7. Post Type Key: location
8. save changes
9. Now you should see Locations on the left  of the dash board
10. Hover over Locations and click add new.
    - The default youll see Add title, description and to the right featured image. 
    - We will need to add other fields like address, Phone, Business Hours
11. Now we will create custom fields.
12. Go back to dash board, and hover over ACF and click Field Groups and add Field Groups. 
13. For the Field Group Title up top, we will call this Location Details as this is where more of the locations details will live and later be called and used in the dynamic tags to populate and show our dynamic data on the page. 