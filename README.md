# grocerybill.java
START
    PROMPT user for coupon amount
    IF coupon amount > 1.0 OR coupon amount <= 0.0
        SET coupon amount to 0.10 (10%)
    ENDIF

    PROMPT user for grocery bills for weeks 1 to 4
    STORE weekly bills in an array
    CALCULATE monthly total as the sum of weekly bills
    CALCULATE weekly average as the monthly total divided by 4

    CALCULATE monthly total with coupon as monthly total * (1 - coupon amount)
    CALCULATE weekly average with coupon as monthly total with coupon divided by 4

    DISPLAY monthly total and weekly average without coupon
    DISPLAY monthly total and weekly average with coupon
END
