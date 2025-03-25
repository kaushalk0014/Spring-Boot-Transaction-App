Isolation Level
-------------------------------
Read Uncommitted
Read committed
Repeatable Read
Serializable

-------------------------------
    => Optimistic Locking
    => Pessimistic Locking

        * Optimistic Locking: It a vased on version locking 
            We can achive optimistic locking using anntation @Version
        
       *Pessimistic Locking
           Pessimistic locking is locking row/object level using annotation
           @Lock(LockModeType.PESSIMISTIC_WRITE)
           
