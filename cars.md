## Table name: cars

- id: PK BIGINT AI NOT NULL UNIQUE 
- price: DECIMAL (8,2) NULL
- brand: VARCHAR (50) NOT NULL
- model: VARCHAR (50) NOT NULL INDEX
- color: VARCHAR (50) NULL
- doors: TINYINT NULL 
- seats: TINYINT NULL
- body_type: VARCHAR (10) NULL
- fuel_type: VARCHAR (10) NOT NULL
- engine_size: SMALL INT NULL
- horse_power: CHAR (3)
- gearbox AUTO: TINYINT NOT NULL  
- KM: FLOAT (8,0) NULL
- traction: VARCHAR (20) NULL 
- plate number: CHAR (7) NULL UNIQUE
- vin: CHAR (17) UNIQUE NULL
- owners: TINYINT NULL
- year: YEAR NOT NULL INDEX
- mont: MONTH NULL
- status: VARCHAR (20) NULL 
- is_available: TINYINT DEFAULT(0)
- description: TEXT NULL
- notes: TEXT NULL
Ui