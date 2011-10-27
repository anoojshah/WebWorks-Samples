# UI Examples Sample Application

This sample demonstrates how to replicate some different types of common BlackBerry&reg; UI concepts for a BlackBerry Smartphone using HTML and CSS.

The sample code for this application is Open Source under the [Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0.html).


**Author(s)** 

* [Tim Neil](https://github.com/tneil)

## Tested On

* BlackBerry Torch 9860 v7.0.0.x

These examples have been designed for a Smartphone screen size and **not** for the BlackBerry&reg; PlayBook&trade;

**Requires BlackBerry WebWorks SDK for Smartphones v2.0 or higher**


## Dependencies

1. In order to use the spinner on the Input Control Examples [you require the assiciated SpinnerControl extension](https://github.com/blackberry/WebWorks-Community-APIs/tree/master/Smartphone/SpinnerControl) 


## TODOs and Known Issues

* There are some focus based navigation mode issues that still need to be resolved
* Fix the screen height issue where the bottom of the screen shows the app background color
* Fix the layout issues with Pill Buttons 
* Fix the layout issues with Tabs 
* Fix the layout issues on input controls 
* Add more JavaScript toolkit functionality to bbUI.js
* Find a way to embed the toolkit image files in bbUI.css as base64 encoded images
* Need to add Drop down buttons
* Need to add check box controls

## How to Build

To build the UI Examples sample application:

1. Click on the **Downloads** button at the top right of this screen.
2. Select **Download.zip** and save the downloaded file to your local machine.
3. Create a new folder on your local machine named **UIExamples** (e.g. **c:\webworks\UIExamples**).
4. Open the downloaded ZIP file from step 2 and **extract the contents from inside the top level folder** to your new **UIExamples** folder.  This ensures that the necessary application assets, such as **config.xml**, are correctly located at the top level of the **UIExamples** folder (e.g. **c:\webworks\UIExamples\config.xml**).
5. Using an achiving utility (e.g. WinZip or 7-zip), package the contents of your **c:\webworks\UIExamples** folder into a ZIP archive named **UIExamples.zip**.  This archive should have the application assets (not a folder containing the application assets) at its top level.
6. Using the [BlackBerry WebWorks SDK for Smartphones](http://us.blackberry.com/developers/browserdev/widgetsdk.jsp), package the **UIExamples.zip** archive into a BlackBerry Smartphone application using the following command line: **bbwp c:\webworks\UIExamples\UIExampes.zip**


## Contributing Changes

Please see the [README](https://github.com/blackberry/WebWorks-Samples) of the WebWorks-Samples repository for instructions on how to add new Samples or make modifications to existing Samples.


## Bug Reporting and Feature Requests

If you find a bug in a Sample, or have an enhancement request, simply file an [Issue](https://github.com/blackberry/WebWorks-Samples/issues) for the Sample and send a message (via github messages) to the Sample Author(s) to let them know that you have filed an [Issue](https://github.com/blackberry/WebWorks-Samples/issues).

## Disclaimer

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO 
EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR 
THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Change Log

**Oct 26, 2011**

* Focused changes to make it work for BB7 devices.. I will degrade back to BB6/BB7 after BB7 is working well
* Changed main index screen to be more like a BlackBerry list like found in the Options area
* Added Animation effects from Alice.js
* Renamed the x-ww tags to x-bb tags
* Renamed the ww object to bb
* Renamed webworks.js to bbUI.js
* Renamed webworks.css to bbUI.css
* Added a settings example
* Added a page loader to load the different pages in as div's

**Oct 27, 2011**

* Updated the highlight gradient colors
* Added more fixes to the Settings example
* Added more fixes to the Input controls example
* Fixed some screen sizing issues
* Removed the old input.css that was no longer needed

