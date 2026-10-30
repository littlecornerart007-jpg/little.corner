# Little Corners

Cute decor. Simple prices. Made your way.

## What this is

Little Corners is a one-file online shop for a handmade decor brand. Tagline: Cute decor. Simple prices. Made your way.

## Products

| Product | Price | Colour |
|---|---|---|
| Bow-Tied Buddy Pen Stand | ₹99 | Soft white with a red bow |
| Lilac Ribbed Planter | ₹250 | Lavender purple |
| Sunny Bow Planter | ₹250 | Sunny yellow with a pink bow |
| Artificial Mini Snake Planter | ₹99 | Green |

## Pages

- Home
- Shop all and Planters
- Product pages (photo, price, details, care, shipping)
- Bag and checkout
- Make it yours (custom-order form)
- Our little story
- Owner area (orders and requests saved on the device)

## Orders and delivery

- Every order adds a flat Rs. 99 delivery charge.
- Orders and custom requests are sent to littlecorner.art007@gmail.com through Web3Forms, and saved to a Google Sheet.
- The Web3Forms access key is already set in W3_KEY in index.html (it is a public key, safe in the page).
- If the automatic send is blocked, the customer sees a link that opens an email with the details filled in.

## Ask Little Corners AI

- A chat button on every page. Customers describe what they need, their budget and colours.
- Shop products are shown with photo, price and link. Prices come only from the product list, never from the AI.
- Custom ideas (for example pipe-cleaner flower bouquets and flower clips) are labelled as made to order, with no price. A button sends them to the custom-order form with details filled in.
- Unclear requests get one follow-up question.
- Built-in rules work on their own. The AI is used when available, and the rules take over if it is not.
- To use a server-side AI, set CHAT_ENDPOINT in index.html to your function URL. Keep the API key on the server only.

## Edit your products

- Open index.html and find the P list near the top of the script.
- Change a name, price, colour or text, then save.
- Update the TAGS line so the assistant knows the search words for each product.
- Photos are stored inside the file. Ask Claude to swap them if you need new ones.

## Put it online with GitHub Pages

- Create or open your repository on GitHub.
- Upload index.html and README.md using Add file, then Upload files.
- Go to Settings, then Pages, choose branch main and folder / (root), and save.
- Your site appears at https://anshdeepshandilya-ux.github.io/little-corner/ after a minute or two.
- Send a test order to check the email arrives.
