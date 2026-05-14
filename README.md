# cylindricalbox-maker

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A web-based tool to generate OpenSCAD code for creating customized cylindrical boxes, ready for 3D printing.

The simple interface provides four input fields for your box's dimensions and a text area where the corresponding OpenSCAD code is generated instantly.


![A screenshot of the cylindricalbox-maker user interface. It shows input fields for Diameter (50)
, Height (30), Side Thickness (3), and Bottom Thickness (2). Below these is a button labeled "OpenSCADコード生成" and a large text area containing the generated OpenSCAD code.](https://user-images.githubusercontent.com/158352/230704983-0931584c-0056-4b05-b040-522f77c68882.png)

## Demo

Try it live: **[https://code4fukui.github.io/cylindricalbox-maker/](https://code4fukui.github.io/cylindricalbox-maker/)**

## Features

-   Customize box dimensions: diameter, height, side wall thickness, and bottom thickness.
-   Instantly generates OpenSCAD code based on your parameters.
-   Simple, functional layout for both desktop and mobile browsers.

## How to Use

1.  **Open the tool:** Visit the [demo page](https://code4fukui.github.io/cylindricalbox-maker/).
2.  **Set your dimensions:** Enter the desired values in millimeters for the box's diameter, height, side wall thickness, and bottom thickness. The code is generated on page load and updates when you click the button.
3.  **Copy the code:** Select and copy the entire generated code from the text area.
4.  **Render your model:** Paste the copied code into the OpenSCAD editor. This will render your custom cylindrical box, which you can then export for 3D printing.

## Requirements

To use the generated code, you will need [OpenSCAD](https://openscad.org/), a free software for creating solid 3D CAD objects.

## License

MIT License — see [LICENSE](LICENSE).