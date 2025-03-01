# TIBCO Cloud<sup>&trade;</sup> Integration - Develop / TIBCO Flogo® Enterprise Samples<sup>&reg;</sup>

[This](https://github.com/TIBCOSoftware/tci-flogo) repository is the place to find the docs, samples and tools to build Flogo applications as well as build extensions. There are a few ways you can help us:

In this folder, you will find below samples - 

* [HelloWorld](/samples/app-dev/hello-world)
* [Array Manipulations Samples](/samples/app-dev/Array-Operations)
* [Bookstore REST API](/samples/app-dev/rest-api)
* [Branching & Error Handling](/samples/app-dev/branching-errorhandling)
* [Subflows](/samples/app-dev/subflows)
* [Loops](/samples/app-dev/loops.sample)
* [JSON Path](/samples/app-dev/json.path.sample)
* [Array Filtering](/samples/app-dev/array.forEach.sample)
* [EMS](/samples/app-dev/ems.sample)

Please navigate to these samples and go through the respective readme to understand what the sample does.

## Import a sample

1. Download the sample's .json file.

2. Create a new empty app.
![Create an app](import-screenshots/2.png)

3. On the app details page, select Import app.
![Select import](import-screenshots/3.png)

4. Browse on your machine or drag and drop the .json file for the app that you want to import.
![Import your sample](import-screenshots/4.png)

5. Click Upload. The Import app dialog displays some generic errors and warnings as well as any specific errors or warnings pertaining to the app you are importing. It validates whether all the activities and triggers used in the app are available in the Extensions tab.
![The Import app dialog](import-screenshots/5.png)

6. You have the option to import all flows from the source app or selectively import flows.

7. Click Next. If you had not selected a trigger in the previous dialog, the flows associated with that trigger are displayed. You have the option to select one or more of these flows such that the flows get imported as blank flows that are not attached to any trigger. By default, all flows are selected. Clear the check box for the flows that you do not want to import. If your flow(s) have subflows, and you select only the main flow but do not select the subflow, the main flow gets imported without the subflow. Click Next.

## Help

Please visit our [TIBCO Cloud<sup>&trade;</sup> Integration documentation](https://integration.cloud.tibco.com/docs/) and TIBCO Flogo® Enterprise documentation on [docs.tibco.com](https://docs.tibco.com/) for additional information.
