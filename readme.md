Until this project is complete i will keep a diary, or log, of my progress. This file will be replaced with an acrtual readme file as you know it.

I was at the local park when i walked past a small library on a stick. I had seen them before while driving in a city but never stopped. At the park i walked up to this one and inspected it closer. There were various books inside, topics for children, young adult etc etc. You take one to read, you put it back. You add a book. Very community driven. But i thought to myself it would be cool if you could check the inventory before going out here.
That is where the idea for creating an app that tracks the book selection at your LFL. It does depend on the community to update however that falls in line with what the [Local Free Library](https://littlefreelibrary.org/) is all about.

I attempted at first, like many ideas, to go big. Worldwide, dive into the API listing all 100k plus locations, but once I was denied access to the API. I thought to myself, lets start small. Get an MVP out there at least. SO i start this with my local LFL, the one I drove past.

## SO on with it.

Started with a simple bootstrap starter page, to get somethings on the wall. Since i am not able to obtain the API data file, (probably for the better). The idea is, a user can use the link to the LFL map to obtain their LFL Charter Number. This is a unique number applied to each LFL. Back to my website, by entering in the charter number, you are taken to a page where -1) if an inventory list has already been created for that charter number, a list of books will appear with the ability edit, 2) if no database exists for that charter, you can create one and add/edit books.
