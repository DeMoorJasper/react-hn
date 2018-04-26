# Parcel vs webpack performance test using [react-hn](https://github.com/insin/react-hn)

Tested on a dual-core mid-2014 Macbook Pro 13"

| Type | Parcel (Using 2 workers) | Webpack |
| ---  | ---    | ---     |
| Build | *7.76s* | 10.20s |
| Build (cached) | *629ms* | N/A |
| Serve | *3.17s* | 4.01s |
| Serve (cached) | *833ms* | N/A |

## These are false results!

These tests could probably be optimised for both parcel and webpack

Feel free to open a PR :)