<h3 align="center">A Ecom Price Tracking Application</h3>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🔗 [Links](#links)

## <a name="introduction">🤖 Introduction</a>

Developed using Next.js and Bright Data's webunlocker, this e-commerce product scraping site is designed to assist users in making informed decisions. It notifies users when a product drops in price and helps competitors by alerting them when the product is out of stock, all managed through cron jobs.


## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- Bright Data
- Cheerio
- Nodemailer
- MongoDB
- Headless UI
- Tailwind CSS

## <a name="features">🔋 Features</a>

👉 **Header with Carousel**: Visually appealing header with a carousel showcasing key features and benefits

👉 **Product Scraping**: A search bar allowing users to input Amazon product links for scraping.

👉 **Scraped Projects**: Displays the details of products scraped so far, offering insights into tracked items.

👉 **Scraped Product Details**: Showcase the product image, title, pricing, details, and other relevant information scraped from the original website

👉 **Track Option**: Modal for users to provide email addresses and opt-in for tracking.

👉 **Email Notifications**: Send emails product alert emails for various scenarios, e.g., back in stock alerts or lowest price notifications.

👉 **Automated Cron Jobs**: Utilize cron jobs to automate periodic scraping, ensuring data is up-to-date.

and many more, including code architecture and reusability 

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/kunal7219/pricetracker.git
cd pricetracker
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
#SCRAPER
BRIGHT_DATA_USERNAME=
BRIGHT_DATA_PASSWORD=

#DB
MONGODB_URI=

#OUTLOOK
EMAIL_USER=
EMAIL_PASS=
```

Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on these specific websites from [BrightData](https://brightdata.com/), [MongoDB](https://www.mongodb.com/), and [Node Mailer](https://nodemailer.com/)

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## <a name="links">🔗 Links</a>

Assets used in the project are [here](https://drive.google.com/file/d/1v6h993BgYX6axBoIXFbZ9HQAgqbR4PSH/view?usp=sharing)
