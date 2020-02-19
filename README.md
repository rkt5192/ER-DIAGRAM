For my pet shop entity relationship diagram, I added six tables. These included: enclosure, customer, pets, food purchase, pet purchase, and food. For the pets the primary key was the pet ID, this serves as the upc for the animal. The foreign key was pet name so that I could link it to the pet purchases. Other attributes I added were animal age and animal classification. The classification would be the class of the animal (phylum, kingdom, etc.). For food purchase the primary key was order id which serves as the upc. The foreign key was food name so that I could link it to the food purchases.The other two attributes were food quantity and price. For pet purchase I had order ID as the primary key which served as upc. The foreign key was pet name to link to the foreign key from the pets table. I also added breed and quantity as attributes. For food the primary key was food ID and the foreign key was food name. The other two attributes was a boolean for whether it was in liquid form and the temperature. For customer the primary key was loyalty id. The attributes were customer id, home city, zipcode, state and email. For the enclosure, the PK was enclosure id (upc). The attributes were temperature, a boolean for aquatic or terrarium, and the enclosure size. Every relationship was one to many, other than the enclosure to pets. This was because you can one enclosure to every pet, but one purchase for many items. 
