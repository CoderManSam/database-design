- As a customer, so I can receive my tickets, I want to provide my contact information.
    -Entities: user(contact), ticket (movie), contact
- As a customer, so I can decide which movie I want to watch, I want to see a list of movies.
    -Entities: user, movie (screen, time), list of current movies (movie)
- -As a customer, to know where I need to go I want to know which screen is assigned to which movie 
    - Entities: user, screen(movie), movie
- As an admin, so I can manage the movies shown at the cinema, I want to update the list of movies.
    - Entities: user, movie, list of current movies
-As an admin/manager, so I can keep track of tickets customers have purchased I want customers to have a ticket history
    -Entities: user, ticket, ticket history(ticket)
-As an admin/manager, so I can send customers updated lists of movies I'd like to have customer contact information to provide them with the lists
    -Entities: user, list of movies
-As an admin so I know which movies are being played at which screens and when I'd like screens to display what films they're playing and when
    -Entities: user, screen, movie
-As an admin, as the number of screens will increase in the future I'd like the number of screens and number of films being played to be updatable
    -Entities: user, screen, movie


-As a customer, I may want to buy tickets for someone else
    -Entities: user, contact, order