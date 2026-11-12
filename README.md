# FoodApp

FoodApp is a design for a mobile app that lets people order food for pickup or delivery from local restaurants. This repository holds the visual mockups, the brand assets and a sample of the order data the app would exchange with a server. There is no app code yet.

## What is in the design

The mockup walks through a full ordering flow on an iPhone-sized screen:

1. Welcome screen, sign in, sign up and forgot password
2. Choose delivery or pickup
3. Use GPS or type an address
4. Restaurant list and category list
5. Dish detail with toppings and options
6. Cart, checkout and payment (card or cash)
7. Review order and a thank you screen

## Repository layout

| Path | Contents |
| --- | --- |
| `mockup.sketch` | The full mockup, as a Sketch file (open with Sketch on macOS) |
| `Assets/PNGs/` | Exported screens, numbered in flow order, plus the back arrow icon at 1x, 2x and 3x |
| `Assets/logo.sketch`, `Assets/logo.psd`, `Assets/logo-2.psd` | Logo source files |
| `Assets/Chopsticks.psd` | Chopsticks illustration source |
| `Assets/Aristotelica Full Family/` | The Aristotelica font family used in the design (see Credits) |
| `JsonObj.json` | Example of the JSON an order request or response could use: restaurant, items, toppings, payment and customer. All values are sample data. |

## Tech stack

- Sketch and Photoshop for design files
- PNG exports for viewing without any design tool
- JSON for the sample order format

## How to view it

You do not need to install anything to look at the design.

1. Open the screens in `Assets/PNGs/` in order, starting with `1. Welcome Screen.png`.
2. To edit the design, open `mockup.sketch` in [Sketch](https://www.sketch.com/) on macOS. Photoshop is needed for the `.psd` files.
3. To inspect the order format, open `JsonObj.json` in any text editor.

Quick preview of one screen:

![Restaurant list screen](Assets/PNGs/4.%20Restaurant%20List.png)

## Status

Prototype. The design flow is complete, but nothing is implemented. There is no code to build or run and no backend. Restaurant names, addresses, prices and payment details in the mockups and in `JsonObj.json` are placeholders.

## Credits

- Design and concept by Max Awad (2018).
- The mockup uses the Aristotelica typeface by Zetafonts, bought through MyFonts. The font files remain under the Zetafonts license in `Assets/Aristotelica Full Family/Licenses/`, and that license does not cover reuse in other projects. If you fork this project, get your own copy of the font.
