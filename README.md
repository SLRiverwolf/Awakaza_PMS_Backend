# Awakaza_PMS_Backend
Property Management System targeted towards medium to large scale hotels. Developed using Laravel with the guidance of Circlebook Pvt Ltd with automated housekeeping, billing, admin Portal, Front operations, Back operations domains.

Original repository is private.
https://github.com/circlebook/Awakaza-pms-back-end
System and code could be demonstrated upon request with permission of the company.

Commit History:
*   8165ab5 (HEAD -> geethaka) Merge remote-tracking branch 'origin/tehan' into geethaka
|\  
| * b1cb235 (origin/tehan) blacklist
* | 5d11001 (origin/geethaka) last minute updates
* |   7d57be7 Merge remote-tracking branch 'origin/aysha' into geethaka
|\ \  
* | | 76d2d26 reservation mail added'
| |/  
|/|   
* |   dad31e5 tehan merge
|\ \  
| * | fee8147 blacklistUsers
| | | * eb25c4a (origin/aysha) updated payer info
| | |/  
| | * 0452653 update_mealplan
| |/  
|/|   
* | e9bc9e9 delete option for reservations
* |   20ef2dc Merge remote-tracking branch 'origin/aysha' into geethaka
|\ \  
| * | 37890a6 meal plan
| |/  
* | dc95931 billing list page developed
* | 4f49bec dashboard graph mechanics updated
* | 356fa2e working on dashboard
|/  
| *   1c5afa3 (origin/gayathri) Merge remote-tracking branch 'origin/geethaka' into gayathri
| |\  
| |/  
|/|   
* | 5815628 query updated
* | 2cca176 house keeping auto set checkedin rooms to dirty daily
* | a870e57 miniBar updating feature with bill log  completed
* | 6a01e95 billing part added to reservation
* | e198e86 reservattions checkIn, checkOut feature completed
* | d98aa3a got the miniBar standard stock fetch to work using ajax request
| * 497da35 create page of  maintaining rooms
| *   cf4b7f8 Merge remote-tracking branch 'origin/geethaka' into gayathri
| |\  
| | | *   b8b72d1 (origin/sandarekha) create update_minibar page
| | | |\  
| | |_|/  
| |/| |   
| * | | a9af122 Connected backend to clean room list
| * | |   1b2e92c Merge remote-tracking branch 'origin/geethaka' into gayathri
| |\ \ \  
| * | | | 47b83b5 rooms to be cleaned page created
| | | | *   e7c3379 Merge remote-tracking branch 'origin/geethaka' into sandarekha
| | | | |\  
| |_|_|_|/  
|/| | | |   
* | | | | aae3c40 check in model added
* | | | | 77d3dee check in migration added
* | | | | 6cbfe5c locator edit functionality and locator soft delete functionality added
| | | | *   1dc2d0e Merge remote-tracking branch 'origin/geethaka' into sandarekha
| | | | |\  
| |_|_|_|/  
|/| | | |   
* | | | | 353bc67 reservation process completed
* | | | |   ed68de9 Merge remote-tracking branch 'origin/aysha' into geethaka merge with aysha to fix the reservation system as requested
|\ \ \ \ \  
| * | | | | e8ea8c1     modified:   app/Http/Controllers/ReservationController.php new file:   database/migrations/2023_03_23_103126_meal_plan.php modified:   routes/api.php
* | | | | | 483a1ca tehan's guest profile issue fixed
* | | | | |   cb17232 Merge remote-tracking branch 'origin/tehan' into geethaka Guest profile and email feature
|\ \ \ \ \ \  
| |_|_|_|/ /  
|/| | | | |   
| * | | | | 37bdc8b guest profile controller
* | | | | | a68a0a3 houseKeeping commenting feature dev, autodistributioin of rooms to be checked using a scheduling function added
| |/ / / /  
|/| | | |   
* | | | | 4a5bcaa Aysha reservation room fileter query fixed
* | | | | da15056 aysha room filter
* | | | |   2427e0e Merge remote-tracking branch 'origin/aysha' into geethaka Merging aysha'a reservation system. Pending part to be completed
|\ \ \ \ \  
| |_|_|/ /  
|/| | | |   
| * | | | 3f0c7ff       modified:   app/Http/Controllers/ReservationController.php modified:   app/Http/Controllers/payerinfoController.php modified:   app/Models/payerinfo.php modified:   app/Models/reservation.php new file:   app/Models/reserved.php modified:   database/migrations/2023_02_01_131109_create_payerinfo.php modified:   database/migrations/2023_02_06_170715_create_reservation_table.php new file:   database/migrations/2023_03_18_090810_create_reserved_table.php modified:   routes/api.php
| * | | |   17b89fc Merge remote-tracking branch 'origin/geethaka' into aysha
| |\ \ \ \  
| * | | | | 075ff70 modified:   app/Http/Controllers/ReservationController.php modified:   app/Http/Controllers/payerinfoController.php modified:   app/Models/reservation.php modified:   database/migrations/2023_02_06_170715_create_reservation_table.php modified:   routes/api.php
| * | | | | 21e0185     modified:   .gitignore new file:   app/Http/Controllers/ReservationController.php modified:   app/Http/Controllers/payerinfoController.php modified:   app/Models/User.php modified:   app/Models/payerinfo.php modified:   app/Models/reservation.php modified:   database/migrations/2023_02_01_131109_create_payerinfo.php modified:   database/migrations/2023_02_06_170715_create_reservation_table.php modified:   routes/api.php
| * | | | |   e0e426b Merge remote-tracking branch 'origin/geethaka' into aysha
| |\ \ \ \ \  
| | | |_|/ /  
| | |/| | |   
* | | | | |   82ead9b Merge remote-tracking branch 'origin/tehan' into geethaka
|\ \ \ \ \ \  
| | |_|_|/ /  
| |/| | | |   
| * | | | | 17783e9 editGRC function added
| * | | | | 14582c1 newgrc
* | | | | | b046a97 backup frequency change option added
* | | | | | 526bbac Auto backup feature added to backend
* | | | | | 2c28cc6 migration room size added
| |_|_|/ /  
|/| | | |   
* | | | | 8647852 migration updated
|/ / / /  
* | | |   5256b7d Merge remote-tracking branch 'origin/sandarekha' into geethaka
|\ \ \ \  
* | | | | bccd8d4 Room Management: room add, room details update features completed
| | | | * fb476dd Merge remote-tracking branch 'origin/aysha' into sandarekha
| | |_|/| 
| |/| |/  
| | |/|   
| | * | bc7e048 payer info connected to database
| * | | 257a341 Created Minibar item page
|/ / /  
* | / 5be56d1 migrations_updated
| |/  
|/|   
* | 633cb4e commented out foreign key constraints from migrations
* |   a7615e8 changes accepted from dev grc model for merging
|\ \  
| * | dff14cb (dev) accepted incoming change from tehan
| * |   ac5fc96 merge with tehan backend. GRC model yet to be edited
| |\ \  
* | | | 7fd76c1 grcModel
* | | |   452789e Merge remote-tracking branch 'origin/tehan' into geethaka
|\ \ \ \  
| |/ / /  
|/| / /   
| |/ /    
| * / 4d68e4a linking
| |/  
* / dc79c3f migrationsCreated
|/  
* 07735ce (origin/development) - Moved user management functions to backend
* afe334d - moved user model and login function to backend - moved locator controller and model to backend - updated api.php
* ae7302c test_revert
* f2cc579 test
* d360ceb (origin/main, origin/HEAD, origin/Chameera, main) Initial commit
* 264540e Initial commit
