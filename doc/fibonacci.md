'''
FUNCTION f(n)
    IF n == 0 THEN
        RETURN 0
    ELSE IF n == 1 THEN
        RETURN 1
    ELSE
        RETURN f(n - 1) + f(n - 2)
    END IF
END FUNCTION

PRINT f(4)
'''