# Kandy Korner Locations

You are going to be building your own React application based off of what you do with these lesson plans for NSS Kennels.

1. Create another React project in `~/workspace/kandykorner` and `cd` into it.
1. Initialize your app with `npx create-react-app .`
1. Create a `src/components` directory.
1. Create your application file and component in `components/KandyKorner.js`.
1. Update `index.js` to render the **`<KandyKorner />`** component, just like you did in Kennels.
1. Make sure your Kandy Korner API is running

## Location Components

Create a directory to hold all of your files for locations, and then create a data module, a list component, and a single item component.

Use the `useEffect` and `useState` hooks in the location list component, get the array of locations from the API. All of this will be nearly identical to Kennels.

Here are the properties for a location.

* Address (string)
* Square footage (number)
* Handicap accessible (boolean)

Create a couple of objects in your `database.json` file to represent some locations, then render all locations in the browser.
