# appa-karenbazon
#https://github.com/kbazon/appa-karenbazon.git

SELECT knjige.naslov
FROM knjige
JOIN autori ON knjige.id_autora = autori.id_autora
WHERE autori.ime_autora = 'Andrić Ivo' 
ORDER BY knjige.naslov ASC;
