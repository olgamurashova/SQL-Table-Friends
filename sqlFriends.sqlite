
CREATE TABLE friends (
  id INTEGER,
  name TEXT,
  birthday DATE
);
INSERT INTO friends (id, name, birthday)
VALUES (1, 'Ororo Munroe', '1940-05-30');
 
SELECT * 
FROM friends;

INSERT INTO friends (id, name, birthday)
VALUES (2, 'Elena Golubeva', '1987-07-13');
INSERT INTO friends (id, name, birthday)
VALUES (3, 'George Anton', '1989-10-13');

UPDATE friends
SET name = 'Storm'
WHERE id = 1;

ALTER TABLE friends
ADD COLUMN email TEXT;

UPDATE friends
SET email = 'storm@codecademy.com'
WHERE id = 1;
UPDATE friends
SET email = 'lalaland@gmail.com'
WHERE id = 2;
UPDATE friends
SET email = 'cleao@gmail.com'
WHERE id = 3;

DELETE FROM friends
WHERE id = 1;

SELECT *
FROM friends;
