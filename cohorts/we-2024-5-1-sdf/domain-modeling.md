# Domain Modeling

**Prerequisites**:

**Requirements**:
- must complete all of these requirements
- must move through requirements in sequential order

<!-- TODO: overview -->

## Record Keeping 📑
- **Points**: 0
- **Requirements**: mark as done
- **Due**: end of week 1
- [Slides](https://github.com/DPI-WE/sdf-record-keeping)
- [Video](https://youtu.be/Pe9b52rmhkQ)

## Must See Movies 🎞️
- **Points**: 2
- **Requirements**: submit
- **Due**: end of week 1
```md
Lets examine an [application](https://msm-associations.matchthetarget.com/) that we'll build in class. It's a very simplified version of the iMDB (the Internet Movie Database).
- Click around it for a minute. Observe and identify:
- How are the URLs named? What is indicated by each part of the URL?
- What all information is being stored and displayed on each page?
- If you had to design tables to store all of the information required to power that app, what would they be? What columns would they have? Think of questions.

**Assignment**: Please submit a list of the tables/columns needed to store all of the information required to power this app.
```
### [Solution: Must See Movies 🎞️ ](./assets/must-see-movies-tables.pdf)

## Records and Relationships 🔗
- **Points**: 2
- **Requirements**: submit
- **Due**: end of week 1
- [Video](https://www.youtube.com/watch?v=2XXdLZNNEFo)
- [Slides](https://github.com/DPI-WE/sdf-records-and-relationships)
```md
This lesson practices domain modeling by discussing when to use a one-to-many or a many-to-many relationship.

**Assignment**: Can you think of another relationship we could model? Is it a one-to-many or a many-to-many? If One-to-Many, which table gets the foreign key column? If Many-to-Many, what’s a good name for the join table?
```

## Photogram 📸
- **Points**: 2
- **Requirements**: submit
- **Due**: end of week 2
- [Slides](https://github.com/DPI-WE/sdf-record-keeping)
- [Video](https://youtu.be/XqHnkDFao4s)
```md
Let's figure out the data model behind [an app called Photogram](https://pg-ajax-1.matchthetarget.com/).

Sign in with one of the existing users (All of their passwords are "password"):
- alice@example.com
- bob@example.com
- carol@example.com
- doug@example.com
- ellen@example.com

Imagine that it's a mockup, and that you've been hired to build an app like that. (Don't come up with additional features or improvements; our job is to build it as it is now.)
What tables and columns will you need? Try to produce a complete list of tables and columns.
I find it helpful to use paper or a spreadsheet to actually draw out all my tables, columns, and try entering in rows to make sure I can record everything necessary for all screens and possible user actions that I can see in the mockup.

**Assignment**: Please submit a screenshot of the entity relationship diagram (ERD) using the [Entity Relationship Diagram (ERD) tool](https://ideas.firstdraft.com)
```

### Entity Relationship Diagram (ERD) tool 📊
```md
Checkout this tool we'll use to create entity relationship diagrams (ERDs) for our projects: https://ideas.firstdraft.com

## Getting started
Once you login you can create a new "Idea" by clicking the green plus icon near the top right of the screen.

![](./assets/erd-tool-1.png)

Once you click that you should see a form where you can choose a name for your project.

![](./assets/erd-tool-2.png)

Once, you've named it click "create" to proceed.

## Adding tables
You can add tables to the canvas by clicking on and dragging the green plus icon onto the canvas.

If the table represents a "user" or someone who will sign up and sign in, check the "User Accounts?" checkbox to get a email and password column.

![](./assets/erd-tool-3.png)

## Adding columns
You can add columns to a table by clicking the green plus icon in the header of a table.

A dialogue should popup and prompt you to choose a column name. You're also required to choose a data type for the column.

![](./assets/erd-tool-4.png)

## Editing columns
If you made a mistake selecting a column's data type or if want to rename that column you can click on the pencil icon next to the column, and the same form will popup and allow to make changes.

![](./assets/erd-tool-5.png)

## Direct associations
To draw a direct association line between two tables and establish a one-to-many relationship, one table needs to have a foreign key column.

This foregin key column must be an Integer type.

Once you have your two tables created with the foreign key column click and drag the id column of the table and drop it onto the foreign key column in the other table.

If everything was successful, a dialogue will popup and the first two questions will prompt you to choose a name for each side of the association.

![](./assets/erd-tool-6.png)

## Indirect associations
In order to draw the dashed indirect association line between two tables and establish a many-to-many relationship, you need to first draw the two direct associations between each table and the connecting join table.

![](./assets/erd-tool-7.png)

Once those direct associations have been built, click and drag the blue double-headed arrow from one of the two tables in the many-to-many and drop it anywhere on the other table.

A dialogue should pop up and ask you to pick which two associations make up the larger many-to-many relationship that you're trying to draw.

Once you select the two associations, you can choose more specific names for each side of the many-to-many.

![](./assets/erd-tool-8.png)
```

## Todo List 📝
- **Points**: 2
- **Requirements**: submit
- **Due**: end of week 2
- [Slides](https://github.com/DPI-WE/sdf-record-keeping)
- [Video](https://youtu.be/XqHnkDFao4s)
```md
Let's figure out the data model behind [this Todo List app](https://ujs-practice-1.matchthetarget.com/)

- Sign up for an account, click around the app, and acquaint yourself with it.
- You can also sign in with the existing user "alice@example.com", password "password".
- Imagine that it's a mockup, and that you've been hired to build an app like that. (Don't come up with additional features or improvements; our job is to build it as it is now.)
- What tables and columns will you need? Try to produce a complete list of tables and columns.
- I find it helpful to use paper or a spreadsheet to actually draw out all my tables, columns, and try entering in rows to make sure I can record everything necessary for all screens and possible user actions that I can see in the mockup.
Slides

**Assignment**: Please submit a screenshot of the entity relationship diagram (ERD) using the Entity Relationship Diagram (ERD) tool
```

## Very Best 🏆
- **Points**: 2
- **Requirements**: submit
- **Due**: end of week 3
- [Video](https://youtu.be/oJEYq0Ygf1E)
- [Slides](https://github.com/DPI-WE/sdf-record-keeping)
```md
Let's figure out the data model behind [an app called Very Best](https://verybest.matchthetarget.com/).

Sign in with one of the existing users (All of their passwords are "password"):
- alice@example.com
- bob@example.com
- carol@example.com
- doug@example.com
- ellen@example.com

Imagine that it's a mockup, and that you've been hired to build an app like that. (Don't come up with additional features or improvements; our job is to build it as it is now.)
What tables and columns will you need? Try to produce a complete list of tables and columns.
I find it helpful to use paper or a spreadsheet to actually draw out all my tables, columns, and try entering in rows to make sure I can record everything necessary for all screens and possible user actions that I can see in the mockup.

**Assignment**: Please submit a screenshot of the entity relationship diagram (ERD) using the first draft Entity Relationship Diagram (ERD) tool
```

## Yap 🍔
- **Points**: 2
- **Requirements**: submit
- **Due**: end of week 3
- [Video](https://youtu.be/FYUK36jEDl0)
- [Slides](https://github.com/DPI-WE/sdf-record-keeping)
```md
Let's figure out the data model behind [this Yelp-clone, Yap](https://yap.matchthetarget.com/).

- Sign up for an account, click around the app, and acquaint yourself with it.
- You can also sign in with the existing user "alice@example.com", password "password".
- Imagine that it's a mockup, and that you've been hired to build an app like that. (Don't come up with additional features or improvements; our job is to build it as it is now.)
- What tables and columns will you need? Try to produce a complete list of tables and columns.
- I find it helpful to use paper or a spreadsheet to actually draw out all my tables, columns, and try entering in rows to make sure I can record everything necessary for all screens and possible user actions that I can see in the mockup.

**Assignment**: Please submit a screenshot of the entity relationship diagram (ERD) using the first draft Entity Relationship Diagram (ERD) tool
```
- [Yap 🍔 (Sample tables/records)](./assets/yap-tables.pdf)

## Offer Right 🤝
- **Points**: 2
- **Requirements**: submit
- **Due**: end of week 4
- [Slides](https://github.com/DPI-WE/sdf-record-keeping)
- [Video](https://youtu.be/Fltvtv9Mltk)
```md
Explore this target application: [Offer Right](https://offer-right.matchthetarget.com/).

It's a simplified version of the real [Offer Up](https://offerup.com/) — a two-sided market. Users can:

- post items to sell
- browse items to purchase
- chat with sellers to make offers
- sellers can mark items as sold once satisfied
- buyers and sellers coordinate meeting up on their own

Sign up for a new account or use our standard (alice/bob/carol@example.com with password of password). Explore and experiment with the features. I suggest taking notes on the following:

- Identify all of the screens in the app.
- On each screen:
  - What information can you see?
  - What actions can you take? Usually, this means: "what links and buttons can you click?"
  - For each action:
    - What screen do you end up on after you take it?
    - What information was created/read/updated/deleted along the way?

Keeping the notes you took above in mind: design a data model that can support all user actions that you observe in app. I.e., a complete listing of tables and columns.

Remember that it's usually helpful to create your tables on paper or in a spreadsheet and entering some sample records to make sure you can record everything you're trying to record, before attempting to create the compact Entity Relationship Diagram (ERD).

**Assignment**: Please submit a screenshot of the entity relationship diagram (ERD) using the first draft Entity Relationship Diagram (ERD) tool
```

### Offer Right (example solution) 🛒 💡
```md
Here is an example solution for the Offer Right assignment:

## Example Solution
There is definitely more than one data model that will work! But here is one example solution. Take a look, compare it to your own, and ask questions if anything is not clear!

ERD ([Entity–relationship model](https://en.wikipedia.org/wiki/Entity%E2%80%93relationship_model))

![](./assets/offer-up-erd.png)

![](./assets/offer-up-associations.png)
```
