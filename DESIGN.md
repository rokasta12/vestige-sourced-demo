---
version: alpha
name: White Vintage Reveal
description: "A clean white ecommerce theme inspired by Bimbo Vintage Club: bold uppercase logo, white gallery space, olive-gold wordmark overlay, and products sliding/revealing from right to left."
colors:
  primary: "#050505"
  bg: "#FFFFFF"
  surface: "#FFFFFF"
  text: "#050505"
  muted: "#6F6F6F"
  line: "#EDEDED"
  accentPink: "#B7A65E"
  accentPinkStrong: "#A8964F"
  softPink: "#FFF3F8"
  saleRed: "#D82727"
  focus: "#111111"
typography:
  logo:
    fontFamily: Archivo Black
    fontSize: 1.75rem
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "0.02em"
  heroWord:
    fontFamily: Archivo Black
    fontSize: 8.5rem
    fontWeight: 400
    lineHeight: 0.9
    letterSpacing: "0.01em"
  heading:
    fontFamily: Archivo
    fontSize: 4rem
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: "-0.02em"
  body:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: "0em"
  label:
    fontFamily: Inter
    fontSize: 0.72rem
    fontWeight: 700
    lineHeight: 1
    letterSpacing: "0.12em"
rounded:
  none: 0px
  sm: 4px
  pill: 999px
spacing:
  xs: 6px
  sm: 12px
  md: 20px
  lg: 40px
  xl: 72px
components:
  button-primary:
    backgroundColor: "{colors.text}"
    textColor: "{colors.bg}"
    rounded: "{rounded.pill}"
    padding: 14px 22px
  button-primary-hover:
    backgroundColor: "{colors.accentPinkStrong}"
    textColor: "{colors.text}"
  button-secondary:
    backgroundColor: "{colors.bg}"
    textColor: "{colors.text}"
    rounded: "{rounded.pill}"
    padding: 13px 21px
---

## Overview

This theme is simple, loud, and product-first. The page should feel like a white studio wall: almost no decoration, big black uppercase VESTIGE logo, and product cutouts moving across the hero. The olive-gold VESTIGE wordmark sits on top of products like a fashion magazine sticker.

## Colors

- **White background:** Main identity. Keep most sections pure white.
- **Black text:** Logo, icons, prices, buttons, and navigation.
- **Olive-gold accent:** Main branding color for the VESTIGE hero wordmark. Also use for small badges, selected states, and hover accents.
- **Light gray line:** Use for thin dividers only. Avoid cards with heavy borders.

## Typography

- Logo and hero word use **Archivo Black** for a heavy uppercase fashion feel.
- Body and commerce UI use **Inter** for readable product info.
- Use uppercase labels with wide letter spacing for categories, filters, and tiny badges.

## Layout

- Header: centered logo, hamburger left, search/cart right, lots of white space.
- Hero: white background, oversized uppercase brand word in olive-gold, product images sliding from right to left.
- Product grid: 2 columns on mobile, 4 columns on desktop, no card border, lots of breathing room.
- Product photos should be cutout/transparent PNGs or white-background images.

## Components

Buttons are simple pills. Primary button is black with white text. Hover can turn olive-gold. Secondary button is white with black border.

## Do's and Don'ts

- Do use product images as the main decoration.
- Do keep backgrounds white.
- Do use large uppercase type.
- Do make animation slow, smooth, and automatic.
- Don't use gradients, neon, shadows, or generic AI landing-page style.
- Don't make product cards look like SaaS cards.
