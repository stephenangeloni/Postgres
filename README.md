# Postgres

DELETE FROM 
    tabA using (
        SELECT 
            keyB 
        FROM 
            tabB
    ) b 
WHERE 
    tabA.keyA = b.keyB;
