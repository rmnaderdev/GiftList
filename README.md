# GiftList

A platform for creating and sharing gift lists with friends and family.

## Goals
- Basic Login/Signup to create lists
- Automatic price updates for Amazon links (history tracking would be cool)
- Ability to click and drag items in list to re-order them
- Statistics print out for items in list
- Create links to share lists with anonymous users (using cuid links)


## Initial Data Structure
- User tables (implemented by better auth)
- Lists table | List instances (one user, many lists)
- List item | Items in a list (name, link, price, notes)
- Price History | Log of price changes for items in a list (timestamp, listItemId, lastPrice, newPrice)


## Technologies Used
- NextJS
- Prisma (Postgres)
- BetterAuth
- 