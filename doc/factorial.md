'''
FUNCTION f(n)
    IF n == 0 OR n == 1 THEN
        RETURN 1
    ENDIF

    RETURN n * f(n - 1)
END FUNCTION

PRINT f(7)
'''