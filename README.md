# commit 7f8a1749d0175fbf2b22409a1f8f6c030fa68a87

Add page skeleton.

# commit 9c61fc2b7348859dd6371fd36346ef6fec8ecc83

Outline the base HTML structure for the layout.

# commit 6860ac09564b3b99df39342fd99591aa37d62eda

A two column layout can be achieved by using 50% (half) width and floating the elements so they align side by side.

# commit 6aecd34631b6a324129c60820ee18db7f1bb0f55

Add background and margins around the elements to provide white space around each tile.

# commit c884d9e7da95f524bed1361bc2a8ebeb8e8a7419

The margin increases the total width of the div which makes the width greater than 50% and causes the boxes to break onto a new line.

We need to add a child container that will take the margin in order to preserve the outer div width of 50%.

# commit 2fa338bcb336cad1552efb7892779a5197f29a54

Add media query for mobile responsiveness.

The tiles should change to 100% when viewed on a phone.

I chose 500px as an arbitrary number, the mobile viewport for various phones will be less than 500px.

# commit 8bfcb5fa3546bd6ab07ae139278ebbcadff59a02

Add styling for year text.

Note that text-align center easily centers the text, but for vertical centering we use `line-height`.

If we know the height of the parent container (we do since we set it to 200px) then we can set the same `line-height` to match the exact parent width; this gives us vertical centering.

# commit

Add basic hover styling.

