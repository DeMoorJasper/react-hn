# Parcel vs webpack performance test using [react-hn](https://github.com/insin/react-hn)

This fork is meant to demonstrate an app that is slightly closer to reality than the hello world benchmark examples. However this is not meant for convincing people to switch to parcel or webpack. This is simply another indication/test.

Use whatever you prefer and fits your project. If you have a enormous project or don't want to configure anything use parcel. If every bit matters or don't want to hit any breaking bugs than your best bet is webpack (although parcel is very stable lately). You could also combine both, use parcel for fast development builds and once the project is ready for launch spend those hours configuring webpack to get that smaller bundle.

Tested on a dual-core mid-2014 Macbook Pro 13"

| Type | Parcel (Using 2 workers) | Webpack |
| ---  | ---    | ---     |
| Build | **6.55s** | 11.15s |
| Build (cached) | **523ms** | 4.82s |
| Serve | 5.29s | **3.64s** |
| Serve (cached) | **1.1s** | 2.16s |
| Incremental builds (after a tiny change) | **239ms** | 552ms |
| Build package size | 194.62KB | **125.63KB** |

## These are false results?!

These tests could probably be optimised for both parcel and webpack

Feel free to open a PR :)
