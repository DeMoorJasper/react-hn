# Parcel vs webpack performance test using [react-hn](https://github.com/insin/react-hn)

Tested on a dual-core mid-2014 Macbook Pro 13"

| Type | Parcel (Using 2 workers) | Webpack |
| ---  | ---    | ---     |
| Build | **7.56s** | 13.99s |
| Build (cached) | **628ms** | N/A |
| Serve | **3.17s** | 3731ms |
| Serve (cached) | **833ms** | N/A |
| Build package size | 194.62KB | **125.63KB** |

## These are false results!

These tests could probably be optimised for both parcel and webpack

Feel free to open a PR :)
