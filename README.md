# Carbon Crunch Assignment

This webpage I designed is made specifically for a **laptop screen** with no media queries implemented for mobile or tablet devices. 
The layout and styling are optimized for larger screens such as a monitor, and elements are not responsive on smaller viewports.

[Live Deployement](https://carbon-crunch-assignment.vercel.app/)

My Approach towards the assignment.

MY DESIGN FLOW -

NAVBAR > Hero Section > Stats Section > Features Section > Services Section

1. NAVBAR -
    - I built this navbar using flexbox for responsive layout.
    - I used DM SANS font for navbar
    - Navbar isdivided into 3 divs - one for logo and company name, menu options using <a>, and buttons

    ![Navbar Preview](assets/nav-prev.png)

2. Hero Section -
    - The section is divided into 2 divs - Description and Image
    - Flexbox is used for responsive layout and span tags for unique colors

    ![Hero Section Preview](assets/hero-prev.png)

3. Stas Section -
    - I used a common class for all of the stats boxes so that I can avoid all the repetitions among the code
    - But every box is different in terms of color so used different CSS class for them.

    ![Stats Section Preview](assets/stats-prev.png)

4. Features Section -
    - I created a parent div that contains all the child feature cards.
    - I used flex-wrap to maintain the arrangement of these cards, so if new cards are added, they would follow the responsive layout.

    ![Features Section Preview](assets/feats-prev.png)

5. Services Section - 
    - Again, this section is also divided into two divs - one for image and one for description

    ![Services Section Preview](assets/service-prev.png)