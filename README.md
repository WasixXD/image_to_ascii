# Image to Ascii

<img src="https://github.com/WasixXD/image_to_ascii/blob/main/homer.jpg">
A Simple Image to Ascii converter in Rust
<img src="https://github.com/WasixXD/image_to_ascii/blob/main/homerascii.png">


## Brief 📖
In my way to learn Rust i decided to make this converter.

## Challenges 🐢
- new to Rust

## Goals 🏆
[ x ] Convert Image to Ascii Art<br>
[ x ] User can choose the resolution and the image

## How it works? 💼
The algorithm makes a Vector of the image's pixels and during the iteration it calculates the luminosity of each one and chooses the best character to be placed

## Installation ⚙️
Clone the repository and with cargo run :
```
$ cargo run
```
## Usage
```
$ cargo run image_name resolution
```
