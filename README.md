# Event_Invitation

## Objective
To design a **visually appealing event invitation** using basic HTML elements and CSS for layout, structure, and presentation.
## Tasks Completed
### 1. Set Up the HTML Document
- Used `<!DOCTYPE html>`, `<html>`, `<head>`, `<title>`, and `<body>`.
- Set the title to **"Event Invitation"**.

#### CSS Styling:
- Background color set to light beige (`#fdf6e3`).
- Applied `font-family: sans-serif;` for clean typography.

### 2. Create the Invitation Container
- Used a `<div>` with class `.invite-card` to wrap content.

#### CSS Styling:
- Applied `width`, `padding`, `border-radius`, and `box-shadow`.
- Centered the card using `margin: auto` and `margin-top`.

### 3. Add Event Title and Subtitle
- Used `<h1>` for event name: **Annual Alumni Meet 2025**.
- Used `<h3>` for subtitle: **In Remembrance of the Spirited Journey**.

#### CSS Styling:
- Center-aligned headings.
- Used custom colors for emphasis.

### 4. Insert Date, Time, and Venue
- Used `<p>` tags to display:
  - **Date:** July 10, 2025
  - **Time:** 1 PM onwards
  - **Venue:** Nalli hall

#### CSS Styling:
- Bolded the labels using `<strong>`.
- Text aligned and spaced using margins/padding.

### 5. Add an Image or Banner
- Used `<img>` for decorative event banner/logo.

#### CSS Styling:
- Applied `max-width: 100%`, `border-radius`, and center alignment.

### 6. Add RSVP or Contact Info
- Included inside a `<footer>` section:
  - RSVP Name
  - Contact Number
  - Email ID
### HTML FILE:
```
<!DOCTYPE html>
<html>
<head>
    <title>Event Invitation</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="invite-card">
        <h1>Annual Alumni Meet 2025</h1>
        <h3>In Remembrance of the Spirited Journey</h3>

        <p><strong>Date:</strong> July 10, 2025</p>
        <p><strong>Time:</strong>  1 PM onwards</p>
        <p><strong>Venue:</strong> Nalli hall</p>

        <img src="logo.png" alt="Event Banner">

        <footer>
            <p>RSVP: Jackson Samuvel</p>
            <p>Contact: +91 98782 55209</p>
            <p>Email: jack7271@gmail.com</p>
        </footer>
    </div>

</body>
</html>
```

### Live WEB PAGE:

### OUTPUT:
![Screenshot 2025-07-08 223250](https://github.com/user-attachments/assets/67860673-15b0-48b7-9bb7-fa6518573b51)

### RESULT:
A simple event invitation webpage using HTML and CSS was created with structured layout, styling, and contact info.
