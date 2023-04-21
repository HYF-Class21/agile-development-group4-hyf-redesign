# HackYourFuture site redesign

## 0. Setup

> Note this is the development strategy for the main page of this website.

- [ ] Boilerplate HTML file
- [ ] empty CSS file
- [ ] CSS file is linked to HTML

---

- This user stories are developed on branch
  [user-personas](https://github.com/HYF-Class21/agile-development-group4-hyf-redesign/tree/user-personas).
- This branch is merged to
  [main](https://github.com/HYF-Class21/agile-development-group4-hyf-redesign/tree/main)
  branch after completion.

---

## Homepage

### 1. Title

- This user story is developed on branch `home-title`
- This branch is merged to `main` branch after completion.

> As a user i want to read the title of the page.

#### - HTML -

- Comment this section
- add `header` tag and define class `top-bar`
- add `div` tag with class `logo`
- add `img` tag with class `logo-image` and define `href`

#### - CSS -

- Comment this section
- add `.header` with display; width; height; min-height; box-sizing; padding.
- add `.logo` with display; justify-content; align-items; height.
- add `.logo-image` with width; height; object-fit; border-radius.

### 2. Navbar

- This user story is developed on branch `home-navbar`
- This branch is merged to `main` branch after completion.

> As a user i want to have a navigation bar with links so i can navigate between
> different pages .

#### - HTML -

- Comment this section
- add `nav` tag nested in `header` and define class `nav-links`
- add 2 `a` tags with class `nav-items` defining an `href`.
- add `span` tags nested into `a` tags.
- add `a` tag with class `nav-btn`, target and text in between tags.

#### - CSS -

- Comment this section
- add `.nav` with padding; justify-content;positionl; box-shadow align-items;
  margin; color; font-family; witdth.
- add `.nav-links` with display;justify-content; align-items.
- add `.nav span` with position; font-family.
- add `.nav-items` with display; align-items; height; color; font-size;
  line-height; text-transform; padding; font-family.
- add `.nav-btn` with display; font size; line-height; text-decoration;
  background-color; color; font-weight; border; border-radius; box-sizing;
  padding; cursor; text-transform; align-items; font-family.

### 3. Main section Description

- This user story is developed on branch `home-description`
- This branch is merged to `main` branch after completion.

> As a user i want to know more about the program offered by HackYourFuture.

<!--#### - HTML -

 Not supposed to be here
- add `section` tag with class `welcome`
- add `div` tag with class `welcome-container`
- add `h1` tag with class `welcome-title`
- add `img` tag with class `welcome-image` and define `src`.
-->

### Add description section

#### - HTML -

- Comment this section
- add `section` tag with class `description-container`
- add `div` tag with class `description`
- add `h2` tag with class `description-title` with text between tags.
- add `p` tag with class `description-p` with text between tags.
- add `a` tag with class `description-btn` defining an `href` value.
- add `button` tag nested in `a` tag.
- add `img` tag with class `description-img`

### Add impact section

#### - HTML -

- Comment this section
- add `section` tag with class `impact`
- add `div` tag with class `impact-container`
- add `h2` tag with class `impact-title` with text between tags
- add `p` tag with class `impact-p`
- add 3 `div` with class `impact-boxes` tags.

#### - CSS -

- Comment this section
- add `.description-container` with display; flex;justify-content; width;
  padding;position; flex.
- add `.description` with width; display; margin.
- add `.description-title` with font-size; line-height; margin-bottom;
  text-transform; font-family; font-weight; color; text-align; max-width.
- add `.description-p` with color; text-align; max-width; line-height;
  font-size;font-family; margin; font-weight.
- add `.description-btn` with border; box-sizing; font-family; font-size;
  font-style; margin; padding; text-decoration; vertical-align.
- add `.button` with display; font-size; line-height; text-decoration;
  font-weight; border; border-radius; box-sizing; padding;
  cursor;text-transform; align-items;font-family; background-color; color.
- add `.description-img` with align-items;box-sizing; display; flex-direction;
  height; justify-content; max-height; max-width; width; position; background;
  flex; margin; padding.

- Comment this section
- add `.impact` with display; justify-content; width; padding; position;
  box-shadow; background; flex.
- add `.impact-container` with display: flex; flex-direction; align-items;
  box-shadow; padding; margin-bottom.
- add `.impact-title` with font-size; line-height; margin-bottom;
  text-transform; font-family; font-weight; color; text-align; max-width.
- add `.impact-p` with color; text-align; max-width; line-height; font-size;
  font-family; margin; font-weight.
- add `.impact-boxes` with display; flex-direction; background-color; width;
  padding.
- add `.impact-boxes h1` with font-size; line-height; margin-bottom;
  text-transform;font-family; font-weight; color; text-align; max-width.
- add `.impact-boxes p` with color; text-align; max-width; line-height;
  font-size; font-family; margin; font-weight.

### 4. Main section Partners

- This user story is developed on branch `home-partners`
- This branch is merged to `main` branch after completion.

> As a user i want to see which partners and collaborators HackYourFuture has.

#### - HTML -

- Comment this section
- add `section` tag with class `partners`
- add `div` tag with class `partners-container`
- add `h2` tag with class `partners-title` with text between tags
- add `div` tag with class `partners-icon-container` with text between tags.
- add 16 `div` tags with class `partners-icon-boxes`

#### - CSS -

- Comment this section
- add `.partners` with display; justify-content; width; padding; position;
  box-shadow; background; z-index; flex;
- add `.partners-container` with display; flex-direction;
  justify-content;align-items; width; max-width; padding; margin.
- add `.partners-title` with margin.
- add `.partners-icon-container` with display; flex-wrap; width;
  justify-content.
- add `.partners-icon-boxes` with align-items; box-shadow; box-sizing; display;
  height; max-height; max-width; width; z-index; position; background; flex;
  margin; padding.

### 5. Main section Form

- This user story is developed on branch `home-form`
- This branch is merged to `main` branch after completion.

> As a user i want to have a `form` where i can write my information and send it
> to HackYourFuture staff.

#### - HTML -

- Comment this section
- add `section` tag with class `form-section`
- add `div` tag with class `form-container`
- add `h1` tag with class `form-title` with text between tags
- add `p` tag with class `form-p`
- add `form` tag with class `form-fields` tags.
- add `label` tag with class `fields-labels`
- add `input` tag with class `fields-inputs`
- add `textarea` tag with class `fields-message`

#### - CSS -

- Comment this section
- add `.form-section` with display; justify-content; width; padding; position;
  box-shadow; background; flex;
- add `.form-container` with display; flex-direction; width; height;
  background-color; padding;
- add `.form-title` with font-size; line-height; margin-bottom; text-transform;
  font-family; font-weight; color; text-align; max-width;
- add `.form-p` with color; text-align; max-width; line-height; font-size;
  font-family; margin; font-weight;
- add `.form-fields` with display; flex-direction; max-width; align-items;
- add `.fields-labels` with color; text-align; max-width; line-height;
  font-size; font-family; margin; font-weight;
- add `.fields-inputs` with border; border-radius; outline; background-color;
  padding; color; width;
- add `.fields-message` with border; border-radius; outline; padding; color;
  background-color; margin-bottom; width;

### 6.Footer

- This user story is developed on branch `home-footer`
- This branch is merged to `main` branch after completion.

> As a user i want to have links to different platforms related to
> HackYourFuture.

#### - HTML -

- Comment this section
- add `footer` element and define class `footer`
- add `div` with class `footer-content`
- add `h2` tag with class `footer-head` and adding some text in between tags.
- add `p` tag with class `footer-text` and adding some text in between tags.
  -add `a` tag with a class `footer-mail` and define an `href` element.
- add `div` with class `footer-links`, define `href` value and adding text in
  between tags.
- add 4 `a` with class `footer-icons`, define `href`, target and
- add an `img` tag inside `a` tags. with class `icon` and define `src` to an
  asset.

#### - CSS -

- Comment this section
- add `.footer` with padding; justify-content;positionl; box-shadow align-items;
  margin; color; font-family; witdth.
- add `.footer-content` with align-items; display;flex-direction; height;
  auto;justify-content;width;position; static background; flex; margin ;padding.
- add `.footer-head` with font size; margin-bottom; text-transform; font-family;
  font-weight; color; max-width
- add `.footer-text` with text-align; font size; margin-bottom; text-transform;
  font-family; font-weight; color; max-width; line-height; margin.
- add `.footer-mail` with text-align; font size; margin-bottom; text-transform;
  font-family; font-weight; color; max-width; line-height; margin.
- add `.footer-links` with position ; background; display; align-items; height;
  margin-bottom; justify-content; font-family; font-weight; color; max-width;
  max-height; max width; margin.
- add `.footer-icons` with color; text-align;max-width; line-height; font-size;
  font-family; margin; font-weight.

## Volunteers

> Note this is the development strategy for the main page of this website.

### 1. Title Volunteers

- This user story is developed on branch `volunteers-title`
- This branch is merged to `main` branch after completion.
  > As a user I want to read the title of the page.

#### - HTML -

- Comment this section
- add `header` tag and define class `top-bar`
- add `div` tag with class `logo`
- add `img` tag with class `logo-image` and define `href`

#### - CSS -

- Comment this section
- add `.header` with display; width; height; min-height; box-sizing; padding.
- add `.logo` with display; justify-content; align-items; height.
- add `.logo-image` with width; height; object-fit; border-radius.

### 2. Navbar Volunteers

- This user story is developed on branch `volunteers-navbar`
- This branch is merged to `main` branch after completion.
  > As a user i want to have a `navbar` so i can navigate between different
  > pages.

#### - HTML -

- Comment this section
- add `nav` tag nested in `header` and define class `nav-links`
- add 2 `a` tags with class `nav-items` defining an `href`.
- add `span` tags nested into `a` tags.
- add `a` tag with class `nav-btn`, target and text in between tags.

#### - CSS -

- Comment this section
- add `.nav` with padding; justify-content; position; box-shadow align-items;
  margin; color; font-family; witdth.
- add `.nav-links` with display; justify-content; align-items.
- add `.nav span` with position; font-family.
- add `.nav-items` with display; align-items; height; color; font-size;
  line-height; text-transform; padding; font-family.
- add `.nav-btn` with display; font size; line-height; text-decoration;
  background-color; color; font-weight; border; border-radius; box-sizing;
  padding; cursor; text-transform; align-items; font-family.
- add underline element under the nav button of the page when active on it

### 3. Intro section

- This user story is developed on branch `volunteers-intro`
- This branch is merged to `main` branch after completion.
  > As a user i want to volunteer for HackYourFuture.

#### - HTML -

- Comment this section
- add `section` tag with class `volunteer-intro-container`
- add `div` tag with class `volunteer-intro`
- add `h2` tag with class `volunteer-intro-title`
- add `p` tag and include a description of what it's like to be a coach at HYF
- add `div` tag with class `volunteer-intro-buttons`
- add 2 `a` tags with href links and text in between tags

#### - CSS -

- Comment this section
- add `.volunteer-intro-container` with display; justify-content; width
- add `.volunteer-intro` with align-items; display; flex-direction;
  justify-content; margin
- add `.volunteer-intro-title` with font-size; margin-bottom; text-transform;
  font-family; font-weight; color
- inside `.volunteer-intro` for `p` tag add color; text-align; max-width;
  font-size; font-family; margin
- add `.volunteer-intro-buttons` with align-items; display; flex-direction;
  justify-content; margin
- for `a` tags inside `.volunteer-intro-buttons` add display; font-size;
  background-color; color; font-weight; border; border-radius; padding; cursor;
  text-transform; align-items; font-family

### 4. Volunteer testimonials

- This user story is developed on branch `volunteers-testimonial`
- This branch is merged to `main` branch after completion.
  > As a user i want to know what is like to volunteer for HackYourFuture.

#### - HTML -

##### Part 1

- Comment this section
- add `section` tag with class `volunteers-testimonial-container`
- add `div` inside `section` with class `volunteers-testimonial-1`
- add `div` inside `volunteers-testimonial-1` div with class `testimonial-img-1`
- add `div` inside `volunteers-testimonial-1` div with class `testimonial-1`
- add `h4` tag with class `volunteer-testimonial-name`
- add `p` tag with class `volunteer-testimonial-position`
- add `p` tag with class `volunteer-testimonial-text`
- inside `testimonial-1` add `a` tag with class `volunteer-discover`

##### Part 2

- Comment this section
- add `section` tag with class `volunteers-testimonial-container`
- add `div` inside `section` with class `volunteers-testimonial-2`
- add `div` inside `volunteers-testimonial-2` div with class `testimonial-img-2`
- add `div` inside `volunteers-testimonial-2` div with class `testimonial-2`
- add `h4` tag with class `volunteer-testimonial-name`
- add `p` tag with class `volunteer-testimonial-position`
- add `p` tag with class `volunteer-testimonial-text`
- inside `testimonial-2` add `a` tag with class `volunteer-discover`

#### - CSS -

- Comment this section
- add `.volunteers-testimonial-container` with display; width; justify-content;
  padding
- add `.volunteers-testimonial-1` with display; width; justify-content;
  align-items
- add `.volunteers-testimonial-2` with display; width; justify-content;
  align-items
- add `.testimonial-img-1` with display; width; min-width; order
- add `.testimonial-img-2` with display; width; min-width; order
- add `.testimonial-1` with display; flex-direction; align-items; max-width;
  order
- add `.testimonial-2` with display; flex-direction; align-items; max-width;
  order
- add `.volunteer-testimonial-name` with font-size; font-family; font-weight;
  color; text-align
- add `.volunteer-testimonial-position` with color; text-align; font-family;
  font-weight
- add `.volunteer-testimonial-text` with color; text-align; font-size;
  font-family;
- add `.volunteer-discover` with display; font-size; background-color; color;
  font-weight; border; border-radius; padding; cursor; text-transform;
  align-items; font-family

### 4. Footer Volunteers

- This user story is developed on branch `volunteers-footer`
- This branch is merged to `main` branch after completion.

> As a user i want to have links to different platforms related to
> HackYourFuture.

#### - HTML -

- Comment this section
- add `footer` element and define a class `footer`
- add `div` with class `footer-content`
- add `h2` tag with class `footer-head` and adding some text in between tags.
- add `p` tag with class `footer-text` and adding some text in between tags.
  -add `a` tag with a class `footer-mail` and define an `href` element.
- add a `div` with class `footer-links`, define `href` value and adding some
  text in between tags.
- add a 4 `a` with class `footer-icons`, define `href`, target and
- add a `img` inside `a`tags. define class `icon` and define `src` to an asset.

#### - CSS -

- Comment this section
- add `.footer` with padding; justify-content;position; box-shadow; align-items;
  margin; color; font-family; witdth.
- add `.footer-content` with align-items; display;flex-direction; height;
  auto;justify-content;width;position; static background; flex; margin ;padding.
- add `.footer-head` with font size; margin-bottom; text-transform; font-family;
  font-weight; color; max-width
- add `.footer-text` with text-align; font size; margin-bottom; text-transform;
  font-family; font-weight; color; max-width; line-height; margin.
- add `.footer-mail` with text-align; font size; margin-bottom; text-transform;
  font-family; font-weight; color; max-width; line-height; margin.
- add `.footer-links` with position ; background; display; align-items; height;
  margin-bottom; justify-content; font-family; font-weight; color; max-width;
  max-height; max width; margin.
- add `.footer-icons` with color; text-align;max-width; line-height; font-size;
  font-family; margin; font-weight.

---
