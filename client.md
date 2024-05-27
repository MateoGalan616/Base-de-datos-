# Tarea en clase semana 8 
## la funcion count
### Creacion de la tabla 
'''
CREATE TABLE IF NOT EXISTS client (
    id SERIAL PRIMARY KEY,
    nul VARCHAR(10) NOT NULL,
    fullname VARCHAR(10) NOT NULL,
    phone VARCHAR(10),
    city VARCHAR(10),
    credit_limit DECIMAL(5,2)
);
'''
### insercion de datos 
'''
INSERT INTO client (fullname, phone, city, credit_limit)
VALUES 
('John Doe', '1234567890', 'Quito', 999.99),
('Jane Smith', '0987654321', 'Guayaquil', 999.99),
('Michael Johnson', '1357902468', 'Cuenca', 999.99),
('Emily Davis', '9876543210', 'Machala', 999.99),
('William Brown', '2468013579', 'Ambato', 999.99),
('Olivia Wilson', '9876543210', 'Loja', 999.99),
('James Taylor', '1234567890', 'Manta', 999.99),
('Sophia Martinez', '4567890123', 'Portoviejo', 999.99),
('Benjamin Anderson', '5678901234', 'Esmeraldas', 999.99),
('Emma Hernandez', '6543210987', 'Ibarra', 999.99);

INSERT INTO client (fullname, city, credit_limit)
VALUES 
('David Garcia', 'Cuenca', 999.99),
('Ava Lopez', 'Quito', 999.99),
('Joseph Gonzalez', 'Guayaquil', 999.99),
('Mia Perez', 'Machala', 999.99),
('Daniel Robinson', 'Loja', 999.99);
'''

### count names 
![image](https://github.com/MateoGalan616/Base-de-datos-/assets/117777169/3a12ab40-45bf-4894-9160-2dc39f2b7af9)

### count phone 
![image](https://github.com/MateoGalan616/Base-de-datos-/assets/117777169/d6fd585a-0df7-4715-877c-8dcaa2c1e269)

### count phone and names 
![image](https://github.com/MateoGalan616/Base-de-datos-/assets/117777169/c96e1569-5fcb-48d0-8209-123ecab0e09e)

### count phone and names and total(*)
![image](https://github.com/MateoGalan616/Base-de-datos-/assets/117777169/30e6be04-56c4-4fd6-aa17-9a06ed6153b1)

### count city with distimet 
![image](https://github.com/MateoGalan616/Base-de-datos-/assets/117777169/b7078dd2-7d60-4829-a7ea-e58bb6f36f8c)
