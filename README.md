### Apple ProRes 4444 to WebM Converter
This macOS app allows users to effortlessly convert Apple ProRes 4444 files into WebM format while preserving the alpha channel. Ideal for live content assets, overlay animations, or any project requiring high-quality transparency retention.

**Features**

- Drag-and-drop functionality for ProRes 4444 files.
- Outputs WebM files with alpha channels intact.
- Self-contained: no additional installations or dependencies required.
- Apple Silicon-only compatibility for optimised performance.

**How to Use**
This app is specifically designed for creators who need to convert ProRes 4444 files with alpha channels into WebM format for use in live content setups. It’s perfect for assets like overlays, transitions, and animations that require transparency in tools such as StreamElements, OBS, or other live production software. Below, you’ll find a step-by-step guide tailored for your needs.

**1. Download the App**

- Visit the GitHub Repository (replace this link with your repository link).
- Download the latest release:
  - Click Releases (found in the right-hand sidebar).
  - Select the latest version and download the .zip file.
- Unzip the file:
  - Double-click the .zip file to extract the .app file.

**2. Prepare Your Files**

Before starting, ensure you have your ProRes 4444 files with an alpha channel ready. These are typically files exported from video editing tools like Final Cut Pro or Adobe Premiere Pro.

You can choose to convert:
- A Single File: Use this if you want to convert one animation or graphic.
- An Entire Folder: Use this if you have multiple files that need conversion.

**3. Launch the App**
- Open the app by double-clicking the .app file.
- You may encounter a security prompt (if macOS doesn’t recognise the developer):
  - Go to System Preferences > Security & Privacy > General.
  - Click Open Anyway next to the app name.

**4. Convert Files**
- Option A: Convert a Single File
  - Drag and drop your ProRes 4444 file directly into the app.
  - Click the Convert button.
  - The app will process your file and save the WebM file in the same folder as the original file.
- Option B: Convert Multiple Files in a Folder
  - Drag and drop an entire folder containing ProRes 4444 files into the app.
  - Click the Convert button.
  - All the files in the folder will be processed, and the WebM versions will be saved in the same folder.

**5. Verify the Output**
- Navigate to the folder where your original files are stored.
- Confirm that the new .webm files have been generated.
- Check the files in your live content software (e.g., OBS or StreamElements) to ensure the alpha channel has been preserved.

**6. Troubleshooting**
- If a File Doesn’t Convert:
  - Ensure the input file is in ProRes 4444 format with an alpha channel. Files without an alpha channel will still convert, but the transparency will not be preserved.
  - Ensure the file isn’t corrupt or incomplete.
- If the App Doesn’t Open:
  - Double-check that you’re using a macOS Apple Silicon device (the app is not compatible with Intel Macs).
  - Go to System Preferences > Security & Privacy and allow the app to run.

**Tips for Usage**
- File Naming: Ensure your files have clear and unique names to avoid overwriting during conversion.
- Destination Folders: Double-check that the app has write permissions for the folder where the output files are saved.
- Testing: Use tools like OBS to test the WebM files and confirm the transparency works as expected.

**7. Feedback and Future Updates**
This app is designed to streamline a very specific workflow, but I’m open to feedback or suggestions. If you encounter any issues or have feature requests, feel free to submit them on the GitHub repository under the Issues tab.

By following these instructions, you should have no trouble converting your ProRes 4444 files into WebM format while retaining the alpha channel. Let me know if you have any questions or need additional guidance!

**Target Audience**
This app is designed for:

- Content creators that need high quality animations with alpha channels, but can't find a usable converter.
- Video editors working with transparent assets... maybe?
- Professionals looking for a streamlined workflow without manual setups... yeah, I am reaching now.

**Limitations**

- Currently compatible with macOS (Apple Silicon only).
- Not tested or supported on Intel Macs.
