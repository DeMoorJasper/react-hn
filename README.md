# Parcel vs webpack performance test using [react-hn](https://github.com/insin/react-hn)

This fork is meant to demonstrate an app that is slightly closer to reality than the hello world benchmark examples. However this is not meant for convincing people to switch to parcel or webpack. This is simply another indication/test.

Use whatever you prefer and fits your project. If you have a enormous project or don't want to configure anything use parcel. If every bit matters or don't want to hit any breaking bugs than your best bet is webpack (although parcel is very stable lately). You could also combine both, use parcel for fast development builds and once the project is ready for launch spend those hours configuring webpack to get that smaller bundle.

Tested on a dual-core mid-2014 Macbook Pro 13"

| Type | Parcel (Using 2 workers) | Webpack |
| ---  | ---    | ---     |
| Build | **7.56s** | 13.99s |
| Build (cached) | **628ms** | N/A |
| Serve | **3.17s** | 3.73s |
| Serve (cached) | **833ms** | N/A |
| Build package size | 194.62KB | **125.63KB** |

## These are false results!

These tests could probably be optimised for both parcel and webpack

Feel free to open a PR :)
